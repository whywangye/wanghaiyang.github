<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
	<title>图书管理系统</title>
<script type="text/javascript" src="../js/index.js"></script>
</head>

<style type="text/css">
	*{
		margin:0px;
		padding: 0px;
	}
	td{

		text-align: center;
	}
   ._main{
   width: 800px;
  margin: 0px auto;
  border: 2px solid black;

   }

   ._table{
   width: 100%;

   }
 ._font{
 	font-size: 40px;
 	font-family: "华文行楷";
 	text-align: center;
    color: red;
 }
 
</style>



<body>

<div class="_main">
	
<table class="_table" border="1" id="myTable">
	<tr>
		<td colspan="5" class="_font">图书管理系统</td>

	</tr>

    <tr>
    	<td>编号</td>
    	<td>书名</td>
    	<td>作者</td>
    	<td>价钱</td>
    	<td>出版社</td>
    </tr>
</table>





</div>



<button  id="mybutton" value="提交">提交按钮</button>



</body>
</html>
