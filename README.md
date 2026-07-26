# vic-blog
更符合现代审美的博客系统 优秀的插件主题系统 超高的扩展性 

✨ 特性亮点
本系统由东方博客二开 感谢东方博客开源 
本系统已集成评论回复 主题插件 发布创作 abc权限系统 支持管理员 超级管理员 创作者 阅读者和自定义权限
支持回复评论醒等功能，支持 Markdown。无限嵌套回复。
灵活的侧边栏: 可自定义展示最新文章、最多阅读、标签云等模块。
支持浅色/深色主题自动切换
高性能缓存: 原生支持缓存
SEO 自动优化和手动优化: SEO 功能，新内容发布后可自动通知主流浏览器。
支持自由制作上传主题和插件 扩展性极高 已内置12个实用插件
内置图床功能，方便图片上传和管理。

🚀 快速开始
1. 环境准备
推荐php74系统 mysql5.4
下载zip包到网站目录下 解压后访问对应域名即可进入手动安装页面
在plugins目录下可上传插件


🤝 贡献指南
我们热烈欢迎任何形式的贡献！如果您有好的想法或发现了 Bug，请随时提交 Issue 或 Pull Request。

基于东方博客系统
1.优化index.php语法错误
2.优化sysclient ssl验证关闭
3.优化install.lock位置问题
4.修改 common.php 支持主题 functions.php 
自动加载5.修复后台插件管理页面支持卸载功能
6.优化文章内容处理支持短代码
7.更新默认主题的 theme.json
——
涉及修复部分
includes/classes/Plugin.php
# 插件系统增强
includes/classes/SysClient.php
# SSL证书验证修复
includes/common.php
# Session优化 + 主题functions.php支持
admin/controllers/plugin_api.php
#插件卸载功能
admin/views/plugins.php          
#后台插件管理界面
themes/default/single.php 
#短代码支持
install/index.php
#安装锁位置修复

❤️ 支持与赞助
如果本项目帮助到了你，请在这里留下你的网址，让更多的人看到。您的回复将会是我继续更新维护下去的动力。
演示站点veom.cn
