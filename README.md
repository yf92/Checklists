## WeiBoNoAD——非官方的微博客户端

### 先看两个截图
<img src="https://raw.githubusercontent.com/dyike/WeiboNoAD/master/img/weibo1.png" width="280px" height="498px" /><img src="https://raw.githubusercontent.com/dyike/WeiboNoAD/master/img/weibo2.png" width="280px" height="498px" />

### 为什么要写这个项目？

* 作为一个曾经微博的实习生，虽然最后入职上出现了小问题，内心对微博还是很有感情。
* 微博客户端现在的timeline乱得一塌糊涂，刷的微博都是几天前，都是以前看过的，所以不得不自己撸一个客户端。
* 作为一个业余的swift爱好者，对于swift从入门到再次入门，反正现在这个项目是在swift3的版本下开搞的，算是练手的项目吧。

### 此项目目前还有哪些没有完成以及存在的问题？

* 这个嘛，我一直往下写，功能点逐步完成，目前只完成了首页的timeline。还存在好多问题，微博内容文字的排版，行与行之间的间距跟官方客户端还是有很大的差距，毕竟这是在模仿。
* 图片浏览，在上图方面还存在比例缩放的问题。图片的清晰度还是可以的，建议在wifi模式下刷微博。
* 转发评论点赞没有完成。
* 消息提醒和私信功能没有完成。我在考虑要不要把私信功能单独出来。
* 个人信息页没有完成，我在考虑怎么做减法，官方的内容太多太杂！

### 如何安装体验？

* 作为一个业余的爱好者，我没有iOS开发者账号，所以现在也没有办法发布蒲公英这样的平台上让大家下载。
* 如果你想在我的基础上继续折腾，你可以clone下来，然后将WeiBoCommon.swift文件中AppKey/AppSecret之类信息替换成你自己的，这个信息你可以在open.weibo.com上创建自己的应用获取自己的信息。这里我就不截图描述了。
* 如果你还是想体验的话，可以直接git clone下来项目，然后执行pod install,前提你需要有一台mac。微博私信@做手艺 体验“WeiboNoAD”，我将添加你的微博id到体验列表中。
* 发现问题可以告诉我哟，我们一起来把这个项目做好哟！

### 感谢！

* 感谢@安正超 超哥提供了一些资源素材，比如微博表情图片
* 感谢@告别青春，老乡亲给以帮助，开发过程中遇到的问题，我谷歌不到答案的，都帮忙解决了。
* 感谢@没有故事的卓同学，我同事，ios老司机——安利我写swift的，结果就拿微博来练手的，也给以指导了。

### 最后想说的！

* 来一起来踩swift的坑吧！还是挺有意思的。