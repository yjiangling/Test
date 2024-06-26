# Test
## 标题1
### 标题2
#### 标题3

*This text will be italic*

**This text will be bold**

// xingshiyi （分类形式一，使用星号，后面要留空格）
* item1
* item2
* item3      

// xingshier （分类形式二，使用短划线，后面要留空格）
- item1
- item2
- item3    

// xingshisan （分类形式三，使用数字，后面要留空格）
1. item2
2. item2
3. item3     

// xingshisi （分类形式四，多级目录使用不同的分类符合，后面要留空格）
1. item
   + item1
   + item2


// yin yong wen ben （插入引用文本内容）
> 尝试插入多行引用内容，下一行回车后会自动补上引用符号，实际显示效果可能只有一行，取决于输入的引用内容总长度

// 插入代码块，每一行使用制表符或者四个空格，首行代码前、末行代码后都要留一行空格

    mlflow run /data/asr-ctc-training \
    -P data_dir=/data/asr-ctc-training/dvc \
    -P batch_size=64 \
    -P num_epochs=100 \
    -e train \
    --run-name nvtest \
    --env-manager local

// 插入超链接，中括号[]内输入标题，后面小括号()中输入对应的网址

[Markdown使用说明](https://www.codenong.com/cs105974878/)

[GitHub中markdown语法使用说明](https://raw.gitcode.com/mirrors/guodongxiaren/test/raw/master/README.md)

[Emoji表情](https://raw.gitcode.com/mirrors/guodongxiaren/test/raw/master/emoji.md)

- [X] 评估
- [x] 开发
- [x] 测试
- [x] 送检
- [ ] 修改
- [ ] 二审
- [ ] 通过


```C++
#include <stdio>
#include <iostream>
#include<regex>
#include <boost/python.hpp>
#include <boost/python/numpy.hpp>
```

```Bash
if [ -f $file ]; then
    echo "file exist"
else
    echo "file not exist"
fi
```

```Python
import numpy as np
import tensorflow as tf
```


表头1  | 表头2|
--------- | --------|
表格单元  | 表格单元 |
表格单元  | 表格单元 |

| 表头1 | 表头2 | 表头3 |
| ------- | ------- | ------- |
| 表格单元 | 表格单元 | 表格单元 |
| 表格单元 | 表格单元 | 表格单元 |

:smile:

|Col1|Col2|Col3|
|:--- |:---:| ---:|
|Row1|Row2|Row3|
|Row4|Row5|Row6|
