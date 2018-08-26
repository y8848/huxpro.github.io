---
layout:     post
title:      "Python+openvpn环境搭建"
subtitle:   ""
date:       2018-08-26 17:00:00
author:     "hryu"
header-img: ""
---




**过程**

<br />

安装Python-->安装pycharm编译器-->cmd-->pip install opencv-Python

<br />

**注意事项**

<br />

首先要导入：
>import cv2 as cv

出现“no module named cv2”的问题。

解决方法：
打开PyCharm，选择file-settings-project-project interpreter,如下图所示。如果打开之后没看到opencv-python 的package，则选择右上角的“+”号搜索opencv-python.



