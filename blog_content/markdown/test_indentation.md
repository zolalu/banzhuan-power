---
title: 测试缩进和空行功能
date: 2024-05-27T01:00:00.000Z
lastModified: 2024-05-27T01:00:00.000Z
tags: 测试,缩进,空行
coverImage: https://images.unsplash.com/photo-1677442136019-21780ecad995?w=800&h=400&fit=crop
---

# 缩进和空行测试

这是一个测试文档，用来验证编辑器的缩进和空行功能。

## 代码块测试

```javascript
function testFunction() {
    if (condition) {
        console.log("这是缩进的代码");
        
        // 空行测试
        
        for (let i = 0; i < 10; i++) {
            console.log(i);
        }
    }
}
```

## 列表缩进测试

### 无序列表
- 第一级列表项
    - 第二级列表项
        - 第三级列表项
    - 回到第二级
- 回到第一级

### 有序列表
1. 第一项
    1. 子项目1
    2. 子项目2
        1. 更深层的子项目
2. 第二项

## 引用块测试

> 这是一个引用块
> 
> 这里有空行分隔
> 
>     这里有缩进的内容
>     继续缩进的内容

## 混合内容测试

这是普通段落。

    这是缩进的段落（4个空格）
    继续缩进的内容

这又是普通段落。


这里有多个空行分隔。

## Python代码示例

```python
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)

# 测试函数
for i in range(10):
    print(f"fibonacci({i}) = {fibonacci(i)}")
```

## 总结

==这个测试验证了编辑器支持：==

1. Tab键缩进功能
2. 空行保留
3. 代码块格式化
4. 列表自动续行
5. 引用块缩进 