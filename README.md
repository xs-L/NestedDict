# 嵌套字典构造与调用的相关功能

## 功能

该程序主要的功能：
- 就是将一个文件中每一行每一列的每一个词转换为嵌套字典
- 读取该嵌套字典


## 举例

1. python环境下运行以下代码即可

> print readDict(getDict('test.csv'))

其中test.csv是我自己定义的文件

2. 文件内容格式为如下

```
实惠;快;优惠;
太长;畅;
太差了;
好;
坏;
好;舒服;小贵;
很快;行;实用;渣;硬;不够光滑;
```

3. 运行程序后，嵌套字典如下

```
{0: '实惠', 1: '快', 2: '优惠', 3: '太长', 4: '畅', 5: '太差了', 6: '好', 7: '坏', 
8: '好', 9: '舒服', 10: '小贵', 11: '很快', 12: '行', 13: '实用', 
14: '渣', 15: '硬', 16: '不够光滑'}
```

嵌套字典被转换为一个list

## 说明

- 代码有详细的注释
- 程序还有优化的空间
- 欢迎star
