---
title: Demo
tag:
  - demo
category:
  - demo
---

test

<!-- more -->

# 示例

## vuep

<div id="app">
  <vuep template="#example"></vuep>
</div>

<script v-pre type="text/x-template" id="example">
<template>
  <div>Hello, ${ name }!</div>
</template>

<script>
module.exports = {
  data: function () {
    return { name: 'Vue' }
  }
}
</script>
</script>

## 代码

```js
var a = 1;
```

## quote

{% cq %}Something{% endcq %}

## note

{% note %}
Header
(without define class style)
{% endnote %}

{% note default %}
Header
(without define class style)
{% endnote %}

{% note primary %}
Header
(without define class style)
{% endnote %}

{% note info %}
Header
(without define class style)
{% endnote %}

{% note success %}
Header
(without define class style)
{% endnote %}

{% note warning %}
Header
(without define class style)
{% endnote %}

{% note danger %}
Header
(without define class style)
{% endnote %}

## tabs

{% tabs t_code_1 %}
<!-- tab 标题一 -->
tab1
<!-- endtab -->
<!-- tab 标题二 -->
tab2
<!-- endtab -->
<!-- tab 标题三 -->
tab3
<!-- endtab -->
{% endtabs %}

## label

{% label @ipsum %} 
{% label primary@dolor sit %}
{% label success@dolor sit %}
{% label info@dolor sit %}
{% label warning@dolor sit %}
{% label danger@dolor sit %}

## caniuse

{% caniuse fetch %}
