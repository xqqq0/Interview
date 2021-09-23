![image.png](https://upload-images.jianshu.io/upload_images/954728-e0ec3d9065c244ed.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# OC底层
* 关于runtime讲解的文章
  * [Objective-C类成员变量深度剖析](http://quotation.github.io/objc/2015/05/21/objc-runtime-ivar-access.html) 
  * [综合性文章iOSRunTimeRunLoopExplore](https://github.com/huang303513/iOSRunTimeRunLoopExplore)
  * [OC最实用的runtime总结，面试、工作你看我就足够了！](https://www.jianshu.com/p/ab966e8a82e2?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weixin-friends&from=singlemessage&isappinstalled=1)
  * [【OC刨根问底】-Runtime简单粗暴理解
](https://www.jianshu.com/p/f900de4a1495?plg_nld=1&plg_auth=1&plg_nld=1&plg_dev=1&plg_uin=1&plg_usr=1&plg_vkey=1&plg_nld=1&plg_uin=1&plg_nld=1&plg_auth=1&plg_usr=1&plg_vkey=1&plg_dev=1)
  * 系列文章  [Objective-C Runtime 运行时之一：类与对象]( http://southpeak.github.io/categories/objectivec/) 
  *  **[神经病院objc runtime入院考试](https://blog.sunnyxx.com/2014/11/06/runtime-nuts/)**
 * Category的本质系列
    * [分类的本质一[MJ底层讲解的文字版本]](https://www.jianshu.com/p/da463f413de7)
    * [轻松学习之一－－Objective-C消息转发](https://www.jianshu.com/p/1bde36ad9938)
  
* runloop
  * [runloop系列文章，结合了autoreleasepool](https://juejin.cn/post/6844904073922101261)
  * [RunLoop总结：RunLoop的应用场景（五）阻止App崩溃一次](https://www.codercto.com/a/102997.html)
  * [iOS程序启动与运转- RunLoop个人小结](https://www.jianshu.com/p/37ab0397fec7)
   * [runloop界面](http://www.cocoachina.com/ios/20181221/25906.html)
   * [解密 Runloop(池神微信群分享过的)](https://mp.weixin.qq.com/s?__biz=MzI5MjEzNzA1MA==&mid=2650264704&idx=1&sn=c32d676f7c8a7803ac795442cd5fc377&chksm=f40685b5c3710ca3c2dc022e6703d3fd5e66545977c9e9fdc63ee71714123f8698639fe6f0a2)
  * [深入理解RunLoop](http://www.cocoachina.com/ios/20150601/11970.html)
  * [iOS开发 之 不要告诉我你会用NSTimer!](https://www.jianshu.com/p/330d7310339d)
  * autorelease
    * [黑幕背后的Autorelease](http://blog.sunnyxx.com/2014/10/15/behind-autorelease/)
    * [iOS - 聊聊 autorelease 和 @autoreleasepool--这篇文章讲了前因后果](https://juejin.cn/post/6844904094503567368)
  
* block 
  * [blcok 详细解析（价值high)](https://www.jianshu.com/p/ee9756f3d5f6)
  * [block 详解（价值middle）](https://imlifengfeng.github.io/article/457/)
  * [ios block详解](https://juejin.cn/post/6844903461327208461)

* KVO & KVC：
  * [iOS开发 -- KVO的实现原理与具体应用](https://www.jianshu.com/p/e59bb8f59302)
  *   [KVO](http://liuduo.me/2018/02/07/kvo-imp/)
  *   [KVC](http://ios.jobbole.com/84954/)
  *   [KVC原理剖析](http://www.cocoachina.com/ios/20180305/22441.html)

# swift 
* [【基本功】深入剖析Swift性能优化](https://mp.weixin.qq.com/s/U95QmOOjeXkk-yC23cuZCQ)

# ios编译相关
* [OS程序员的自我修养-前言（零）](https://juejin.cn/post/6844903912143585288 "https://juejin.cn/post/6844903912143585288")
* [深入浅出iOS编译](https://blog.csdn.net/Hello_Hwc/article/details/85226147)
* 动态库与静态库
  * [iOS里的动态库和静态库·100+赞](https://www.jianshu.com/p/42891fb90304)
  * [动态库和静态库](https://juejin.cn/post/6844903619393749000)
# 内存管理
* weak
  * [iOS底层原理：weak的实现原理(价值high)](https://juejin.cn/post/6844904101839372295)
   * [Objective-C runtime机制(7)——SideTables, SideTable, weak_table, weak_entry_t](https://blog.csdn.net/u013378438/article/details/82790332?spm=1001.2014.3001.5501)
  * [iOS 底层解析weak的实现原理--逻辑混乱，不建议再看了](https://www.jianshu.com/p/13c4fb1cedea)
# 网络和多线程
* 多线程
  * [雷峰NSOperation](http://blog.leichunfeng.com/blog/2015/07/29/ios-concurrency-programming-operation-queues/)
  * [iOS中保证线程安全的几种方式与性能对比](https://www.jianshu.com/p/938d68ed832c)
  * [彻底搞懂OC中GCD导致死锁的原因和解决方案](https://blog.csdn.net/abc649395594/article/details/48017245)
  * [NSMutableArray 线程安全](https://blog.csdn.net/kongdeqin/article/details/53171189)
  * SDW的原理可以在在[一套博客](https://github.com/LeoMobileDeveloper/Blogs)中找到 
  * [SDWebImage优质源码解读笔记（最新版本和旧版本都有）](https://blog.csdn.net/Deft_MKJing/article/details/52900586) 
*   网络知识 
[iOS cookie](https://www.jianshu.com/p/d2c478bbcca5)
    [HTTP 的长连接和短连接](http://blog.jobbole.com/104108/) 
    [TCP/IP常见问题总结（一）](https://blog.csdn.net/superxlcr/article/details/51062472) 
    [TCP/IP常见问题总结（二) ](https://blog.csdn.net/superxlcr/article/details/51083076)
    [TCP/IP常见问题总结（三）](https://blog.csdn.net/superxlcr/article/details/51160170) 
    [TCP/IP常见问题总结（四）](https://blog.csdn.net/superxlcr/article/details/51175591) 
    [网络协议TCP/IP常见问题，TCP/IP必知必会的十个问题](https://www.2cto.com/net/201709/682771.html)
  * [HTTP和HTTPS详解（包含TCP）](https://juejin.im/post/5af557a3f265da0b9265a498#heading-28)
  * NSURLSession 系列
    * [URL加载系统之二：NSURLSession](http://southpeak.github.io/2014/07/11/url-load-system-2/)
* [iOS-UIApplication详解](https://www.jianshu.com/p/f0a2117406d8)



* UI与动画
  * [自定义 ViewController 容器转场](https://objccn.io/issue-12-3/)
  * [View Controller 转场](https://objccn.io/issue-5-3/)
  * [iOS 视图控制器转场详解](https://blog.devtang.com/2016/03/13/iOS-transition-guide/ "iOS 视图控制器转场详解")

* webView
  * **[一文掌握iOS开发中的全部web知识](http://www.cocoachina.com/ios/20190321/26617.html)**
  * [WKWebView使用及注意点(keng)](https://www.jianshu.com/p/9513d101e582) 
  * [从 UIWebView 到 WKWebView](https://www.jianshu.com/p/f94cad074196)

* 数据库
  * [CoreData教程](https://www.cnblogs.com/guogangj/p/3650799.html)
  * [App版本更新时对SQLite数据库升级或者降级遇到的问题](https://blog.csdn.net/jdsjlzx/article/details/50682595)

* 蓝牙
  * [iOS开发系列--通讯录、蓝牙、内购、GameCenter、iCloud、Passbook系统服务开发汇总](https://www.cnblogs.com/kenshincui/p/4220402.html)
  * 另外两篇在掘进上 
  * [iOS开发之玩转蓝牙CoreBluetooth/](http://mrpeak.cn/blog/ios-bluetooth/)

* RN 
  * [React Native的极简手册:很重要](https://www.jianshu.com/p/318342e139c7)
  * [深入浅出 JavaScriptCore](https://www.jianshu.com/p/3f5dc8042dfc)
  * [JSBridge深度剖析](https://blog.csdn.net/xiangzhihong8/article/details/66970600)
  * [JavaScriptCore全面解析 （上篇）]( https://cloud.tencent.com/developer/article/1004875)
  *  [ios7 JavaScriptCore.framework](https://justsee.iteye.com/blog/2036713)
  * [UIWebView与JS的深度交互](http://kittenyang.com/webview-javascript-bridge/)
  * [Objective-C与JavaScript交互的那些事](https://www.jianshu.com/p/f896d73c670a?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weibo)

*   iOS知识体系.
*   优化知识
*   剑指offer

## 面试书籍
*   [iOS 核心动画](https://hit-alibaba.github.io/interview/basic/network/TCP.html)
*   [OSX 高级编程](http://aba.github.io/)
## 综合类博客
* [LeoMobileDeveloper](https://github.com/LeoMobileDeveloper/Blogs)
* [iOSRunTimeRunLoopExplore](https://github.com/huang303513/iOSRunTimeRunLoopExplore)

# 开发工具
* 调试工具
  * [OS/OS X内存管理(二)：借助工具解决内存问题](https://www.jianshu.com/p/09c5141d4531)
* [iOS性能优化：Instrument 调试界面卡顿](https://blog.csdn.net/shaobo8910/article/details/66975785)
## 综合性博客
* [iOS开发：我的初级到中级的晋级之路JHBlog](https://github.com/SunshineBrother/JHBlog)
* [nixzhu的github](https://github.com/nixzhu/dev-blog)
* [音视频](http://msching.github.io/)
* [刘坤的博客](https://blog.cnbluebox.com/blog/2015/05/07/architecture-ios-1/)
* [孙源的博客](https://blog.sunnyxx.com)
* [霜神的runtime和博客](https://halfrost.com/objc_runtime_isa_class/#)
* [南峰子的博客](http://southpeak.github.io/)
* [源码，斯坦福，三方分析](https://knightsj.github.io)
* [综合性文章iOSRunTimeRunLoopExplore](https://github.com/huang303513/iOSRunTimeRunLoopExplore)
* [李峰峰的博客](https://imlifengfeng.github.io)
* [雷纯峰](http://blog.leichunfeng.com/)
* [http://beetree.top](http://beetree.top)
* [ibireme.com/](https://blog.ibireme.com/)
* [伯陽](https://biboyang.github.io/#blog "link to homepage for 伯陽")
* [bang's blog](http://blog.cnbang.net/archives/)
* [J_Knight_](https://knightsj.github.io/)
* [Leo的专栏](https://blog.csdn.net/Hello_Hwc)
* [隔壁老黄](https://github.com/huang303513)

# 面试博客
* [ iOS响应者链 ](http://www.cocoachina.com/ios/20190220/26383.html)
*   [响应者链条-iOS触摸事件全家桶](https://www.jianshu.com/p/c294d1bd963d?utm_campaign=maleskine&utm_content=note&utm_medium=seo_notes&utm_source=recommendation)
*   [runtime](http://southpeak.github.io/2014/10/25/objective-c-runtime-1/)
*   [iOS 保持界面流畅的技巧](https://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/)
*   [如何为一个实例动态替换方法](http://www.bijishequ.com/detail/375654?p=70-64)

*   [Dealloc 时取 weak self 引起崩溃](http://blog.csdn.net/majiakun1/article/details/54944942)
*   [NSObject来世今生](http://www.open-open.com/lib/view/open1477896480457.html)
*   [深浅拷贝](http://www.cocoachina.com/ios/20160512/16231.html)
*   [去哪网iOS消息转发机制与BlocksKit](http://blog.flight.dev.qunar.com/2016/12/29/BlockskitAndiOSMessage/)
*   [消息转发,黄文臣](http://blog.csdn.net/hello_hwc/article/details/49687543)
*   [消息转发](https://www.zybuluo.com/MicroCai/note/64270)
*   [GCD](https://juejin.im/post/5a90de68f265da4e9b592b40)
*   [虚函数表](http://www.learncpp.com/cpp-tutorial/125-the-virtual-table/)
*   [Category 和 Extension 区别](http://www.cocoachina.com/ios/20170502/19163.html)\
*   [Objective-C Category](https://zhuanlan.zhihu.com/p/24925196)
*   [iOS多线程到底不安全在哪里？](https://zhuanlan.zhihu.com/p/23998703)
*   [iOS内存abort(Jetsam) 原理探究](https://satanwoo.github.io/2017/10/18/abort/)
*   [iOS內存abort(Jetsam) 原理探究](http://it.uu01.me/p/oogzof.html)
*   [H5缓存机制浅析-移动端Web加载性能优化【干货】](https://www.jianshu.com/p/509f5dabdb4f)

*   [获取iOS设备的内存状况](https://my.oschina.net/makeffort/blog/90063)


*   crash 捕获机制. 学习 需要了解
*   分类不能添加变量 需要补上
*   缓存设计 需要补上
## 杂项

*   [关联对象 AssociatedObject 完全解析](https://draveness.me/ao)
*   [@selector()的原理](https://www.jianshu.com/p/06de58683f0e)
* [关于宏定义中的do-while(0)循环](https://blog.csdn.net/wangduohuai/article/details/52164174)
## 部分github实现

[大白健康系统KVO, 错误方法](https://github.com/sunday1990/BayMaxProtector)

# 基础回忆
[iOS instancetype和id区别详解](https://imlifengfeng.github.io/article/485/)

# 优化
[UITableView性能优化-中级篇](https://www.jianshu.com/p/04457377b48d)
[iOS 保持界面流畅的技巧（facebook的ASDK的使用）](https://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/)

# 卡顿监控
*   [移动端监控体系之技术原理剖析](http://www.cocoachina.com/ios/20170302/18815.html)
* [美团外卖移动端性能监测体系实现](http://mp.weixin.qq.com/s/MwgjpHj_5RaG74Z0JjNv5g)
*   [微信读书 iOS 质量保证及性能监控](https://wereadteam.github.io/2016/12/12/Monitor/)
*   [网易NeteaseAPM iOS SDK技术实现分享](http://www.infoq.com/cn/articles/netease-ios-sdk-neteaseapm-technology-share)
*   [APM最佳实践系列文章专题合辑](https://github.com/joy0304/Joy-Blog)

*   [手机淘宝：亿级用户APP的快速运维交付实践](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650400312&idx=1&sn=ce8468991c70ab2e06634f59cd2b6865&chksm=83952e20b4e2a736f701853a483da535312a258a56ca87d65b8ef77e8cf012dab9145659a0aa&scene=0&key=459eeebe1b51063320bc30b7024529048032de1a4d3a8e7cf01dbfc995da8f74fe85688c8be0471b1fdcb82d9b875d163a62f42e9ca04946e2c899194097fb93632ca7790f6fb7395d897442b9272213&ascene=0&uin=MTY3NzkzNjI0NA==&devicetype=iMac+MacBookPro12,1+OSX+OSX+10.12.2+build(16C67)&version=12020010&nettype=WIFI&fontScale=100&pass_ticket=JE5tAT8H+fKdFzHQq72mWMIv+itHWOqOma3xmX5OeGGPWz2mPXxz3kaQE1WSKJlw)

## 面试题
*   [【2017年最新】☞ iOS面试题及答案](http://www.cnblogs.com/bossren/p/6401067.html)
*   [源码，斯坦福，三方分析](https://knightsj.github.io)
*   [五月面试提答案基础](https://www.jianshu.com/p/7d486b24dc21)
*   [五月面试题高级](https://www.jianshu.com/p/b6a656c6d129)
*   [五月面试提中级](https://www.jianshu.com/p/48f309a1ab12)
*   [2017年5月iOS招人心得（附面试题](https://juejin.im/post/5aa5f54df265da23906ba68b)
*   [一个渣硕iOS春招总结 | 掘金技术征文](https://juejin.im/post/5ad541e0f265da23994f032c?utm_source=gold_browser_extension)
*   [我的iOS面试之旅](https://juejin.im/entry/5ac0e425f265da23994eac17?utm_source=gold_browser_extension)
* [出一套 iOS 高级面试题](https://juejin.im/post/5b56155e6fb9a04f8b78619b?utm_source=gold_browser_extension)

# 备忘
* 看下UIView和CALayer关系，电子书或者掘金，和[ASDK](https://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/)那篇文章结合起来
* opaque 属性 查一下
* objc_allocateClassPair 和  objc_registerClassPair 的用法 
