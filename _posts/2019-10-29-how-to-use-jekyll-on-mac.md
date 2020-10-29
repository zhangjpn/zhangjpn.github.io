---
layout: post
title: 如何在mac上使用jekyll搭建博客
date: 2019-10-29 23:45:00 +0800
categories: jekyll
---

本文是简单记录在Macbook上搭建jekyll环境维护github博客的文章。

## 环境依赖

关于ruby、jekyll、bundle及其依赖的相关说明。
用一个不大严谨的类比，如果ruby类比于python，那么gem就类比于python模块，bundler类比于pip，jekyll类比于fabric或者各种用python写的命令行工具，gemfile类比于requirements.txt，gemfile.lock类比于依赖的版本锁定记录（python使用同一个文件同时指定依赖和版本）。

## 安装

1. 安装Command Line Tools

```bash
xcode-select --install
```

## 相关命令

```bash
# 安装依赖
bundle install

# 运行本地服务预览效果
bundle exec jekyll serve
```

## 参考文献

[Mac OS X中安装命令行工具Command Line Tools（无Xcode)](https://segmentfault.com/a/1190000018045211)
