# android-google-play-and-other-app-store-review-guidelines-tips

##1.多渠道打包 360被拒
问题说明： 目前多渠道打包一般分忧百度，360等。但目前360和百度互不兼容，如果代码内部包含了非当前的包的代码就会被拒。
问题原因： 百度、360代码互不兼容，如果包含有另外一个的代码就会被拒。

解决方法： 目前多渠道打包还是不够完善的解决这个问题，目前的处理方式。就是打百度包去掉360，打360去掉百度更新。
