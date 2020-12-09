# 第一章：HTML基础

## **1、什么是HTML？**

- HTML 指的是超文本标记语言 （Hyper Text Markup Language）。
- HTML 不是一种编程语言，而是一种标记语言 （markup language）。
- 标记语言是一套标记标签 （markup tag）。
- HTML 使用标记标签来描述网页。

## 2、什么是HTML标签 （HTML tag）？

- 由尖括号包围的关键词。例：<html>
- 标签一般成对出现的，比如 <div> 和 </div>
- 第一个标签叫开始标签（也叫开放标签）和结束标签（也叫闭合标签）

## 3、HTML 的历史

1.  超文本标记语言(第一版) -- 在1993年6月发为互联网工程工作小组(IETF)工作草案发布(并非标准)
2. HTML经历了HTML 2.0、HTML 3.2、HTML 4.0、HTML 4.01、HTML5，共5个版本。最新版本HTML 5于2014年10月28日成为W3C推荐标准。
3. HTML 2.0于1995年11月作为RFC 1866发布，成为第一个正式规范。成为正式规范的目的是为了与当时的各种HTML标准区分开来，故使用2.0作为其版本号。HTML 2.0在RFC 2854于2000年6月发布之后被宣布已经过时。
4. HTML3.0规范是由当时刚成立的W3C于1995年3月提出，提供了很多新的特性，如表格、文字绕排和复杂数学元素的显示。虽然它是被设计用来兼容2.0版本的，但是实现这个标准的工作在当时过于复杂，在草案于1995年9月过期时，标准开发也因为缺乏浏览器支持而中止了。3.1版从未被正式提出，而下一个被提出的版本是开发代号为Wilbur的HTML 3.2，去掉了大部分3.0中的新特性，但是加入了很多特定浏览器，例如Netscape和Mosaic的元素和属性。HTML对数学公式的支持最后成为另外一个标准MathML。HTML 3.2于1997年1月14日成为W3C推荐标准。
5. HTML 4.0同样也加入了很多特定浏览器的元素和属性，但是同时也开始“清理”这个标准，把一些元素和属性标记为过时，建议不再使用它们。HTML的未来和CSS结合会更好。HTML 4.0于1997年12月18日成为W3C推荐标准。
6. HTML 4.01于1999年12月24日成为W3C推荐标准。只是对HTML 4.0的一些微小改进。
7. HTML 5草案的前身名为Web Applications 1.0。于2004年被WHATWG提出，于2007年被W3C接纳，并成立了新的HTML工作团队。在2008年1月22日，第一份正式草案发布。HTML 5于2014年10月28日正式成为W3C推荐标准。

## 4、W3C 标准

- World Wide Web Consortium （万维网联盟）
- 成立于1994年，Web技术领域最权威和最具影响力的国际**中立性技术标准机构**
- https://www.w3.org/
- https://www.chinaw3c.org/

**W3C标准包括：**

- 结构化标准语言（HTML、XML）
- 表现标准语言（CSS）
- 行为标准（DOM、ECMAScript）

## **5、第一个 HTML 文件以及基本结构**

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>hello html</h1>
</body>
</html>
```

- !DOCTYPE 声明必须是 HTML 文档的第一行，位于 <html>  标签之前。

- <!DOCTYPE> 声明不是 HTML 标签，它指示页面使用哪个 HTML 版本进行编写。

- <html> 告知游览器其自身是一个 HTML 文档。lang="en" 表示语言为中文。

- <head>  用于定义文档的头部，它是所有头部元素的容器。常见的头部标签有：<base> <link> <meta> <script> <style> 和 <title> 等。

- meta : 元信息通用标签

  - 常用写法：

    - <meta charset="utf-8" /> : 定义解析文档的格式，建议放在第一行。

    - <meta http-equiv=”content-type”content=”text/html;charset=utf-8” />：同时添加content-type这个http头，并且指定了http编码格式。

    -   <meta name=”viewport”content=”width=device-width,initial-scale=1,minimum-scale=1,masimum-scale=1,user-scalab=no” />：针对viewport的标准的适配移动端的meta元信息

    - description：页面描述，可能被用于搜索引擎或者其他场合。

    - keywords：页面关键字，对于seo场景非常关键。

- title : 文档的标题。

- body： 定义文档的主体。body 元素包含文档的所有内容。





# 第二章：HTML标签

