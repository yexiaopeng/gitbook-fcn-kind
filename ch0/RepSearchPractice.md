# 检索实操

``` cpp
int i = 11;
```

<font face="黑体" color=black><i>我是黑体字<i></font>
<br />
<font face="微软雅黑" color=blue><i>我是微软雅黑<i></font>
<br />
<font face="STCAIYUN" color=red><s>我是华文彩云</s></font>
<br />
<font face="STCAIYUN" color=red><u>我是华文彩云</u></font>


<!-- <center></center> 居中 -->
---
 <table>
        <tr>
            <td><font color=blue>one</font> </td>
            <td>Two</td>
        </tr>
        <tr>
            <td colspan="2"><center>Three</center></td> 
        </tr>
</table>

---
<table>
    <tr>
        <th rowspan="2">真实情况</th>
        <th colspan="2">预测结果</th>
    </tr>
    <tr>
        <td>正例</td>
        <td>反例</td>
    </tr>
    <tr>
        <td>正例</td>
        <td>TP(真正例)</td>
        <td>FN(假反例)</td>
    </tr>
    <tr>
        <td>反例</td>
        <td>FP(假正例)</td>
        <td>TN(真反例)</td>
    </tr>
</table>

--------------------- 

<table>
    <tr>
        <th rowspan="2">真实情况</th>
        <td>预测结果<td>
    </tr>
    <tr>
        <td>正例</td>
        <td>反例</td>
    </tr>
    <tr>
        <td>正例</td>
        <td>TP(真正例)</td>
        <td>FN(假反例)</td>
    </tr>
    <tr>
        <td>反例</td>
        <td>FP(假正例)</td>
        <td>TN(真反例)</td>
    </tr>
</table>
