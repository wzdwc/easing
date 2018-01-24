# easing
 easing是动画function, 包含各种曲线运动
 ## 举个例子
```
    /**
     * 这是一个贝塞尔曲线函数
     * @param  {int} t: 动画已经执行的时间（实际上时执行多少次/帧数）
     * @param  {int} b: 起始位置
     * @param  {int} c: 终止位置
     * @param  {int} d: 从起始位置到终止位置的经过时间（实际上时执行多少次/帧数）
     */
    easeInCubic(t, b, c, d) {
         return c * (t /= d) * t * t + b
    }
  
```
