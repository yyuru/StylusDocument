# **SELECTORS(选择器)**

## **缩进**

  Stylus的代码风格是‘Pythonic’的(即基于缩进的),留白是极其重要的，因此我们用缩进和减少缩进来代替'{'和'}',样例如下所示：

  ``` css
  body
      color white
  ```

  经过编译后：

  ```css
  body{
      color:white;
  }
  ```

  如果个人喜欢的话,可以使用';'将属性和属性值分隔开

  ```css
      body
        color:white
  ```