## 移动手机网页高度问题
-flexible 10rem 宽度试配
-单屏页面 
    iphone 6 667pt
    iphone 6 plus 746pt
    android 在iphone 5s -》iphone
    6plus -》480
    一般不处理高度 scroll-view
    overflow:hidden|scroll
    height 同一设备在微信里
    微信tabbar高度
    微信分享的，微信生态的，应该使用微信开发者工具来进行调试
    怎么解决不同手机的高度？
    不是手机高度有问题 单屏 要展示的内容 不能太多
    z-index+定位+百分比缩放去做这件事
    微信生态 === h5生态
    基本理念，height 是有可为有可不为
    太多的内容再放也放不下 如果安排得当，使用z-index+定位，就可以适当得到在高度小的手机上使用z-index去弥补高度不够的问题
    单屏应用不能太复杂
    等比例缩放 vh rem midia-query
    h5单屏应用 不要急于下手 要先构图
    有可能因为设计题缺少前端知识
    介入进去，