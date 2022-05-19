---
title: 使用 Jekyll 和 Github Pages 构建静态博客
category: 随笔
tags: [博客]
---

# 准备工作

- 假定你会使用 Git 和 Github
- 你懂一线前端的知识
- 你有一定的英语基础

# 创建 Github 仓库

1. 注册 Github 账号；
2. 创建一个名为`<username>.github.io`的仓库，其中`<username>`换成你的用户名；
3. 在仓库的 Settings 里面找到 Pages选项卡，点击 Change theme 按钮，选择主题；
4. 到此为止，你已经成功创建了静态页面，你可以访问 <username>.github.io 来查看你的博客。

官方参考：[创建 GitHub Pages 站点 - GitHub Docs](https://docs.github.com/cn/pages/getting-started-with-github-pages/creating-a-github-pages-site)

# 设置博客的主题

1. 在 Change theme 页面，前往改主题的 github 仓库，将整个仓库的东西搬运到你博客对应的仓库里；
2. 修改`_config.yml`文件，配置你的网站。

# 如何使用 Jekyll 写博客

你只需要把你的文章放在`_posts`文件夹中，Github 会自动处理它。

官方参考：[撰写博客 - Jekyll • 简单静态博客网站生成器 (jekyllcn.com)](http://jekyllcn.com/docs/posts/)

# 进一步设置

- 设置自己的域名
- 给你的博客加上评论功能

# 更多参考资料

- Jekyll：[欢迎 - Jekyll • 简单静态博客网站生成器 (jekyllcn.com)](http://jekyllcn.com/docs/home/)
- Github Pages：[GitHub Pages 文档 - GitHub Docs](https://docs.github.com/cn/pages)
- 给你 Github Pages 加上评论功能：[Beaudar - 表达 (lipk.org)](https://beaudar.lipk.org/)