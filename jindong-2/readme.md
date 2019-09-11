##
SEO ：浏览器后爬取html内容，为了SEO 我们放文字，为了美观  放图片，
场景：网站的 logo  
##  css 选择器 优先级
!important  由高到低
style  (权重1000)
id   (权重100)
class   (权重10)
元素/伪元素 （*）   (权重1)
#box span.active  111
#box span   101
同等优先级 安装css定义的顺序后出现的覆盖先出现的
```css
.red {color: red}
.blue {color: blue}
<span class="red blue">123</span>
```
## animation-fill-mode
forwards: 
none
backwrads: 动画开始前，将元素的样式设为动画第一帧的样式
both:forwards + backwrads

##skew 
1. skew保持两条边平行
2. x 为正值  x不动  y逆时针倾斜
3. y 为正值 y不动  x顺时针