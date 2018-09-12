# transform
### 示例

```
div{
    width:300px;
    margin:150px auto;
    background-color:yellow;
    text-align:center;
    transform:roatate(45deg);       //将div元素顺时针旋转45度
}
```
### 缩放
```
transform:scale();
```
```
div{
    width:100px;
    transform:scale(0.5);       //将div元素缩小一半
    transform:scale(0.5,2);     //水平方向上缩小一半，垂直方向上放大一半
}
```
### 倾斜
```
transform:skew(30edg,30edg);            //水平方向上倾斜30°，垂直方向上倾斜30°，如果只有一个参数，则认为只在水平方向上倾斜，垂直方向上不倾斜
```

### 移动 
```
transform:translate:(50px,50px);            //水平方向上移动50px;垂直方向上移动50px，如果只设置一个参数则认为只在水平方向上移动
```

# 多种变形
```
transform:translate(150px,200px) scale(1.5) rotate(45edg);
//先移动，后旋转，最后缩放，这三个可以进行位置变换，但是会影响最后的显示效果。
```
### 基准点
```
transform-origin:left bottom;       //围绕左下角进行旋转，可以进行自行设置，top center, bottom | left center right值
```
# 3D
### 倾斜
```
transform:rotateX(30deg) rotateY() rotateZ()        //可以只设置一个，也可以设置多个
```
### 缩放
```
transform:scaleX/Y/Z();    //可以在X,Y,Z上面进行缩放，也可以同时在多个轴上缩放，写法如上
```

# 变形矩阵
