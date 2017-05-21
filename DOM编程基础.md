# dom编程

## 编程方式

### 原生代码

- 优点 效率高 灵活性最大
- 缺点 兼容性问题

### 利用库(jq)

>  开发速度快 , 缺少灵活性

- 优点
解决了兼容性问题(1.9版本以下兼容ie6,其他兼容ie9)
提供了非常多的封装方法.
对链式语法支持.

- 缺点

相对于原生速度慢.


## DOM

- d  document  文档
- o  object    对象
- m  model     模型

## 常用方法

> 针对添删改查来整体 api(接口)

### 元素(Element)/标签

- 查
    - document.getElementById()
    - document.getElementsByTagName()
    - document.getElementsByClassName()

- 删除
    - 通过父级删除元素

- 添加
    1. 创建元素(该元素包含的各种属性,事件)
    2. 找到父级
    3. 添加元素

### 属性

- 设置 element.setAttribute(attr,"str")
- 获得 element.getAttribute(attr)
- 删除
    - element.setAttribute(attr,"")(设置为空)
    - element.removeAttribute(attr)

### 文字(内容)

- innerHTML
- innerText

### 常用属性

- `e.id`
- `e.className`
- `e.style`

## 事件

> 什么是事件:

### 鼠标相关事件

### 键盘相关事件

### 其他

## 定时器/延迟器


