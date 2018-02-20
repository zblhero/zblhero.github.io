#中文

##更新内容

增加了新浪微博,Instagram 和 Dribbble 连接的支持

[演示](http://qxxqxx.github.io/blog/greyshade-qiuyin/)
![图片](http://qxxqxx.github.io/images/view.png)

##设置方法

编辑你的 `_config.yml`，加入以下两行

    weibo_user: qzoro # 注：新浪微博自定义网址中用户名部分或数字 ID  http://weibo.com/(此部分内容)
    dribbble_user: #填写Dribbble用户名
    instagram_user: qxxqxx #填写Instagram用户名

##安装方法

在命令行中使用以下命令安装：
	
	$ cd octopress
	$ git clone git@github.com:qxxqxx/Greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss
	$ rake "install[greyshade]"
	$ rake generate

#English

##Updates

I've added support for Weibo,Instagram and Dribbble in social links part.

[Demo](http://qxxqxx.github.io/blog/greyshade-qiuyin/)

##Configuration

Just add following two value in your `_config.yml`

    weibo_user: qzoro # Your weibo id            http://weibo.com/(THIS PART)
    dribbble_user: #Your Dribbble user name
    instagram_user: qxxqxx #Your Instagram user name

##Install

Type the code below in terminal.

	$ cd octopress
	$ git clone git@github.com:qxxqxx/Greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss
	$ rake "install[greyshade]"
	$ rake generate

##Greyshade

[Greyshade](https://github.com/shashankmehta/greyshade) is a minimal, responsive theme for Octopress. From [Shashank Mehta](https://github.com/shashankmehta), based on [Slash](https://github.com/tommy351/Octopress-Theme-Slash)  

[Demo](http://shashankmehta.in/archive/2012/greyshade.html)
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
