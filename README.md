# jquery.imgScroll.js
##一个开源的图片轮播插件
###示例
$("#test").imgScroll({
      imgAdds: ["1.jpg", "2.jpg", "3.jpg","4.jpg", "5.jpg", "6.jpg","7.jpg", "8.jpg",\<br>   "9.jpg","10.jpg"], //图片地址，数组\<br>  
      imgWidth:150,//轮播框大小，以图片张数计算\<br>  
			imgHeight:100,//轮播图片宽\<br>  
			imgHeight:80,//轮播图片高\<br>  
			speed:500,//动画速度，毫秒\<br>  
			imgExplain:['图片1','图片2','图片3','图片4','图片5','6','7','8','9','10'],//图片下图片解释介绍，和图片地址对应，可以不设置，数组\<br>  
			lineMove:false,//是否整个图片框整体移动，默认false，一张一张移动\<br>  
			scroll:true,//是否滚动\<br>  
			scrollSpeed:1500,//滚动速度，毫秒\<br>  
			iconColor:#00bb9c//prev、next图标颜色‘\<br>  
	});\<br>  
