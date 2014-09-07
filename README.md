# Douban login plugin for Discourse / Discourse 豆瓣登录插件

Authenticate with discourse with Douban.

通过豆瓣登录 Discourse。

## Register Client Key & Secert / 申请豆瓣接入

1. 登录[豆瓣开发者中心](http://developers.douban.com/)，注册填写相关信息。
2. 点击`我的应用`，再点击`创建新应用`。
3. 填写相关信息。`网站域名`可填写根域名或者具体域名。如图所示。（验证所需要的标签可在 Discourse 设置中插入，验证后即可删除）
4. 在申请到的后台找到刚申请到的引用，概览中即可以获得`key`和`secret`，将其填入Discourse 设置中。

<img src="https://meta.discourse.org/uploads/default/34525/3041f41ffcde20de.png" width="690" height="463">

## Installation / 安装

Run `rake plugin:install repo=https://github.com/fantasticfears/douban-login` in your discourse directory

In development mode, run `rake assets:clean`

In production, recompile your assets: `rake assets:precompile`

在您 Discourse 目录中运行 `rake plugin:install repo=https://github.com/fantasticfears/douban-login`

在开发者模式下，运行 `rake assets:clean`

在生产模式下，重编译 assets `rake assets:precompile`

## Usage / 使用

Go to Site Settings's login category, fill in the client id and client secret.

进入站点设置的登录分类，填写 client id 和 client serect。

## Issue / 问题

Visit [topic on Discourse Meta](https://meta.discourse.org/t/douban-login-plugin/19736) or [GitHub Issues](https://github.com/fantasticfears/douban-login/issues).

访问[Discourse Meta上的主题](https://meta.discourse.org/t/douban-login-plugin/19736)或[GitHub Issues](https://github.com/fantasticfears/douban-login/issues)。

<img src="https://meta.discourse.org/uploads/default/34526/05ece4662bfe0350.png" width="632" height="500">

<img src="https://meta.discourse.org/uploads/default/34527/fb76e5c6a0e65f66.png" width="690" height="316">

<img src="https://meta.discourse.org/uploads/default/34529/2b2e8e58609dc18f.png" width="690" height="482">

## Changelog

Current version: 0.1.0
