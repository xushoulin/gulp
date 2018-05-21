相信做前端的同学都做过这样的事情，为优化图片，减少请求会把拿到切好的图标图片，
通过ps（或者其他工具）把图片合并到一张图里面，再通过css定位把对于的样式写出来引用的html里面。
对于一些图片较多的项目，这个过程可能要花费我们一天的时间，来实现这步。今天我给大家带来一个工具，
将这一步缩短到几秒钟就能完成，究竟是什么工具这么神奇呢，他就是gulp的一个插件gulp.spritesmith。

  npm install --save-dev gulp 安装gulp

npm install --save-dev gulp.spritesmith 安装 gulp.spritesmith

gulp  运行