# jquery.css3callbacks
css3 动画,过渡回调事件绑定js
调用方式
callback_function:回调函数
type:默认是`false`,-> one事件绑定,只绑定一次,动画判断一次
type:`true`->on事件绑定

```javascript
$('.demo').cssTransitionEnd(callback_function,type);
```
