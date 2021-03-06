# 数组对象

NumPy提供了一个N维数组的类型，即ndarray，它描述了相同类型的“items”的集合。 可以使用例如整数的N来索引项目（items）。

所有的ndarray都是同质的：每个条目占用相同大小的内存块，并且所有块都以完全相同的方式进行解释。如何解释数组中的每个项是由一个单独的数据类型对象指定的，其中一个对象与每个数组相关联。除了基本类型(整数、浮点数等)之外，数据类型对象还可以表示数据结构。

从数组中提取的项（例如，通过索引）由Python对象表示，其类型是在NumPy中构建的阵列标量类型之一。 阵列标量允许容易地操纵更复杂的数据排列。
 
![数组对象](/static/images/threefundamental.png)