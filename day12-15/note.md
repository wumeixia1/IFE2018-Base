这是一个进阶作业，看到设计图的时候，怀疑自己真的优秀到可以实现这个页面。  
实现的过程中，看到页面每部分逐渐实现，有一种攻城掠地的快感。历时几天，设计图是终于是实现了，但将浏览器缩小就看到了问题，其实我也不想写bug的，等技艺精湛之后，来日再战。  
这个过程踩了不少坑，最深有两个，先是抽象相似类的问题，真是考验智商；再者我听从一本书的建议，在一开始就使用`* {box-sizing: border-box;}`重置全部的盒子模型，但使用flex布局的时候，`flex-basis`的计算规则是基于内容盒模型的，以后不能如此单纯地使用。