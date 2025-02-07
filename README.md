![Github Forks](https://img.shields.io/github/forks/Yixin0313/Yixin0313.github.io?style=flat)
![Github Stars](https://img.shields.io/github/stars/Yixin0313/Yixin0313.github.io?style=flat)
![License](https://img.shields.io/github/license/Yixin0313/Yixin0313.github.io)

# 通用个人主页模板：适用于学术和求职场景 | A general-purpose template: suitable for both academic and professional use.

## 预览 | Preview
👉 [Yixin's Homepage](https://yixin0313.github.io/)

## 介绍 | Introduction

这是一个**通用的个人主页模板**，基于 [Sen Li 的学术主页模板](https://github.com/senli1073/senli1073.github.io) 进行修改。  

我新增了**工作经历板块**，使其更加适用于程序员和求职者。并且使用了中英文对照版本。

This is a **general-purpose personal website template**, modified from [Sen Li's academic template](https://github.com/senli1073/senli1073.github.io).  

I have added a **work experience section**, making it more practical for programmers and job seekers.

## 快速开始 | Getting Start
### 1. Fork 该仓库 | Fork this repository
仓库名称应命名为 `<用户名>.github.io`，这样你的个人网站地址将是 `https://<用户名>.github.io/`。

The repository name should be `<username>.github.io`, which will also be your website's URL.


### 2.  编辑页面内容 | Edit page content
(1) 进入你想存放项目的文件夹，并克隆新的仓库 | Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
项目的目录结构如下 | The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) 修改各个板块的内容 | Modify the content of each section, which corresponds to `contents/*.md`.

(3) 调整网站设置 | Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) 替换图片 | Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) 提交更改 | Push it: 
```
git commit -am 'init'
git push
```


### 3. 访问你的网站 | Enjoy

打开浏览器，访问 https://<用户名>.github.io，即可查看你的个人主页

Fire up a browser and go to `https://<username>.github.io`



## License
本项目基于 MIT 许可协议，你可以自由使用和修改此模板。 Yixin Huang 2025年2月7号

Copyright Yixin Huang, 2025. Licensed under an MIT license. You can copy and mess with this template.
