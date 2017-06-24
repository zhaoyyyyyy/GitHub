show.html


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>河北中学</title>
<link href="{CSS_PATH}/hbschool/content.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="{JS_PATH}/jquery.min.js"></script>

</head>

<body>
	<div id="mybody">
    	<div id="top">
        	<div class="menu">
            	<ul>
                	<li>网站首页</li>
                    <li><a href="list.html">学校概况</a></li>
                    <li><a href="#">规章制度</a></li>
                    <li><a href="#">德育网</a></li>
                    <li><a href="#">教研网</a></li>
                    <li><a href="#">名师风采</a></li>
                    <li><a href="#">高考专栏</a></li>
                    <li><a href="#">图书馆</a></li>
                    <li><a href="#">校友会</a></li>
                    <li><a href="#">河中论坛</a></li>
                    <li><a href="#">查询系统</a></li>
                    <li><a href="#" class="specil">东校区</a></li>                    
                </ul>
            </div>           
        </div>
      <div id="dh">
            	<h1><a href="index.html">河北中学首页</a> - <a href="list.html">学校概况</a> - <a href="#">校园文化</a></h1>
            	<div id="search">
            <input name="search" type="text" class="search_text" /><input name="searchbut" type="button" class="search_but" value=" " />
            </div>
          </div>
        <div id="left">
        	<div id="hot">
            	<h2></h2>
                <ul>
                	<li><a href="#">我校举行五四表彰大会暨成人仪式</a></li> 
					<li><a href="#">河北中学4月份家长开放日公告</a> </li>
					<li><a href="#">教育处组织学生收看《2013年中小学… </a></li>
					<li><a href="#">高一年级励志踏青活动花絮 </a></li>
					<li><a href="#">我校组织高一年级励志踏青活动</a></li>
					<li><a href="#">我校举行五四表彰大会暨成人仪式</a></li> 
					<li><a href="#">河北中学4月份家长开放日公告</a></li> 
					<li><a href="#">教育处组织学生收看《2013年中小学…</a></li>
                </ul>
            </div>
          	<div id="pic">
          		<h1></h1>
	           	<div id="colee" >
					<div id="colee1">
					<!-- <p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
					<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
					<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
					<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
					<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
					<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p> -->

                    {pc:content action="position" posid="2" num="3" order="listorder DESC"}{loop $data $v}<p> <img src="{$v['thumb']}" width="200" height="150" />{$v['title']}</p>{/loop}{/pc}
				</div>
				<div id="colee2"></div>
			</div>
        </div>
    </div>
    <div id="right">
        <h1>{$title}</h1>
        <h2>作者：{$username}&nbsp;&nbsp;&nbsp;&nbsp;    图片来源：本站原创&nbsp;&nbsp;&nbsp;&nbsp;     点击数： <span id="hits"></span>&nbsp;&nbsp;&nbsp;&nbsp;     更新时间：{$updatetime}</h2>

            {$content}
            <!-- <p>2013年4月14日，教育处和高一年级组共同组织了高一年级及高二实验部学生“励志踏青”活动。</p>
    		<p>此次“励志踏青”活动，行程约30多华里，历时5个小时。同学们从学校大门南行，左转至燕赵大街直行经历史文化街出南城门过子龙大桥，在南桥头右转进入汊河湿地公园景区，然后向西自由活动到神农庄园停车场集合，沿107国道北行至镇远路右转，到承德街左转北行，经恒山西路返回学校。</p>
    		<p><img src="{IMG_PATH}/hbschool/newspic.jpg" width="550px" height="380px"></p>
    		<p>同学们在此次活动中展现出学校和班级的良好精神风貌。一路上，校旗班旗迎风招展，队伍整齐，每个人脸上都洋溢着青春的笑容。沿途和景区，随处都可以看到同学们捡拾垃圾的身影，互帮互助的身影。在景区，同学们尽情地拥抱大自然，呼吸着自由的空气，和好朋友合影留念。此次活动使同学们在徒步远行中砥砺了意志品质，于集体踏青时领略了湖光水色。</p>
    		<p>此次活动经教育处和高一年级组缜密筹划、精心组织，全体班主任和随队老师的通力配合，在校医校车有利的后勤保障下，获得圆满成功！！</p> -->
        <div class="next"><span class="font_next">上一篇：</span><a href="{$previous_page['url']}">{$previous_page['title']}</a><span class="font_next">下一篇：</span><a href="{$next_page['url']}">{$next_page['title']}</a></div>
      </div>
 
    </div>
	<div id="foot">	  
 	Copyright © 2008－2013 http://www.***.com All Rights Reserved   网站备案：冀ICP备00000000号
	</div>
</body>
<script type="text/javascript" src="{APP_PATH}api.php?op=count&id={$id}&modelid={$modelid}"></script>

</html>


category.html

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>河北中学</title>
<link href="{CSS_PATH}/hbschool/news.css" rel="stylesheet" type="text/css" />

</head>

<body>
	<div id="mybody">
    	<div id="top">
        	<div class="menu">
            	<ul>
                	<li>网站首页</li>
                    <!--<li><a href="#">学校概况</a></li>
                    <li><a href="#">规章制度</a></li>
                    <li><a href="#">德育网</a></li>
                    <li><a href="#">教研网</a></li>
                    <li><a href="#">名师风采</a></li>
                    <li><a href="#">高考专栏</a></li>
                    <li><a href="#">图书馆</a></li>
                    <li><a href="#">校友会</a></li>
                    <li><a href="#">河中论坛</a></li>
                    <li><a href="#">查询系统</a></li>
                    <li><a href="#" class="specil">东校区</a></li>      -->

		{pc:content action="category" catid="0" siteid="$siteid" order="listorder ASC" num="11"}
		{loop $data $v}
		<li><a href="{$v['url']}">{$v['catname']}</a></li>
		{/loop}
		{/pc}                
                </ul>
            </div>           
        </div>
      <div id="dh">
            	<h1><a href="index.html">河北中学首页</a> - <a href="#">学校概况</a> - 所获荣誉</h1>
            	<div id="search">
            <input name="search" type="text" class="search_text" /><input name="searchbut" type="button" class="search_but" value=" " />
            </div>
          </div>
        <div id="left">
        	<div id="leftmenu">
            	<h1>{$catname}</h1>
                <ul>

                	<!--<a href="#">领导简介</a>
                    <a href="#">学校简介</a>
                    <a href="#">光荣历史</a>
                    <a href="#" class="dq">所获荣誉</a>
                    <a href="#">图说河中</a>-->

                    <?php
                        $firstcatid=explode(',', $arrchildid);
                        $firstcatid=$firstcatid[0];   # 存储的是第一个子栏目的id
                    ?>
                    {pc:content action="category" catid="$catid" order="listorder ASC"}
                        {loop $data $v}
                           {if $v['catid']==$firstcatid}
                                <a href="{$v['url']}" class="dq">{$v['catname']}</a> 
                            <?php $curname=$v['catname']; ?>
                           {else}
                                <a href="{$v['url']}">{$v['catname']}</a>
                           {/if}
                        {/loop}
                    {/pc}


              </ul>
            </div>
          <div id="pic">
          <h1></h1>
           	<div id="colee" >
<div id="colee1">
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="images/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="images/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>

</div>
<div id="colee2"></div>
</div>
             
            </div>
        </div>
        
        <div id="right">
        	<h1>{$curname}</h1>
            <ul>
            	<li><a href="#">[组图]我校被授予2010-2011年度省级文明单位</a>	<span class="newsdate">2013-05-10</span></li>
	<li><a href="#">[组图]我校被评为“石家庄市2010-2011年度文明单位”</a>	<span class="newsdate">2013-05-10</span></li>	
	<li><a href="#">[图文]我校被授予“2012年高中教学先进单位”“2012年高中增值奖”等荣誉称号</a>	<span class="newsdate">2013-05-10</span></li>
	<li><a href="#">[组图]我校被授予“河北省体育传统项目学校”荣誉称号</a>	<span class="newsdate">2013-05-10</span>	</li>
	<li>[组图]我校被授予“影子教师”培训基地<span class="newsdate">2013-05-10</span></li>		
	<li>[组图]我校荣获“2010-2012年石家庄市创先争优先进基层党组织荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市妇联系统先进集体称号	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校离退休干部党支部被评为“先进离退休干部党支部”荣誉称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校获得“全国青少年普法教育先进单位”荣誉称号<span class="newsdate">2013-05-10</span></li>	
	<li>[组图]我校荣获“2010年度住房公积金管理先进单位”荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校荣获石家庄市“2010年度实绩突出领导班子”荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市2008—2009年度文明单位光荣称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校党委荣获2009年度先进基层党组织称号<span class="newsdate">2013-05-10</span></li>	
	<li>[组图]我校荣获首批“河北省现代教育技术示范学校”	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校被评为“首届中华百年名校”<span class="newsdate">2013-05-10</span></li>	
	<li>[图文]我校荣获石家庄市“先进基层党组织”荣誉称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校荣获“2007年度实绩突出领导班子”称号<span class="newsdate">2013-05-10</span></li>	
	<li>[图文]我校荣获“2007年度民主评议工作先进单位”荣誉	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市2008年中小学田径运动会“体育道德风尚奖”<span class="newsdate">2013-05-10</span>	</li>
	<li>[组图]我校被石家庄市委市政府评为“双争共建文明校园”	<span class="newsdate">2013-05-10</span></li>
            </ul>
            <div id="page">
	<span class="disabled">前一页</span><span class="current">1</span><a href="#?page=2">2</a><a href="#?page=3">3</a><a href="#?page=4">4</a><a href="#?page=5">5</a><a href="#?page=6">6</a><a href="#?page=2" class="disabled">后一页 
	 </a></div>
        </div>
 
      </div>
 
	<div id="foot">	  
 		Copyright © 2008－2013 http://www.***.com All Rights Reserved   网站备案：冀ICP备00000000号
	</div>
</body>
<script type="text/javascript" src="js/pic.js"></script>
</html>


list.html

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>河北中学</title>
<link href="{CSS_PATH}/hbschool/news.css" rel="stylesheet" type="text/css" />

</head>

<body>
	<div id="mybody">
    	<div id="top">
        	<div class="menu">
            	<ul>
                	<li>网站首页</li>
                    <li><a href="#">学校概况</a></li>
                    <li><a href="#">规章制度</a></li>
                    <li><a href="#">德育网</a></li>
                    <li><a href="#">教研网</a></li>
                    <li><a href="#">名师风采</a></li>
                    <li><a href="#">高考专栏</a></li>
                    <li><a href="#">图书馆</a></li>
                    <li><a href="#">校友会</a></li>
                    <li><a href="#">河中论坛</a></li>
                    <li><a href="#">查询系统</a></li>
                    <li><a href="#" class="specil">东校区</a></li>                    
                </ul>
            </div>           
        </div>
      <div id="dh">
            	<h1><a href="index.html">河北中学首页</a> - <a href="#">学校概况</a> - 所获荣誉</h1>
            	<div id="search">
            <input name="search" type="text" class="search_text" /><input name="searchbut" type="button" class="search_but" value=" " />
            </div>
          </div>
        <div id="left">
        	<div id="leftmenu">
            	<h1>学校概况</h1>
                <ul>
                	<a href="#">领导简介</a>
                    <a href="#">学校简介</a>
                    <a href="#">光荣历史</a>
                    <a href="#" class="dq">所获荣誉</a>
                    <a href="#">图说河中</a>
              </ul>
            </div>
          <div id="pic">
          <h1></h1>
           	<div id="colee" >
<div id="colee1">
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="{IMG_PATH}/hbschool/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="images/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>
<p> <img src="images/pic.gif" width="200" height="150" />2010-2011年度先进单位</p>

</div>
<div id="colee2"></div>
</div>
             
            </div>
        </div>
        
        <div id="right">
        	<h1>所获荣誉</h1>
            <ul>
            	<li><a href="#">[组图]我校被授予2010-2011年度省级文明单位</a>	<span class="newsdate">2013-05-10</span></li>
	<li><a href="#">[组图]我校被评为“石家庄市2010-2011年度文明单位”</a>	<span class="newsdate">2013-05-10</span></li>	
	<li><a href="#">[图文]我校被授予“2012年高中教学先进单位”“2012年高中增值奖”等荣誉称号</a>	<span class="newsdate">2013-05-10</span></li>
	<li><a href="#">[组图]我校被授予“河北省体育传统项目学校”荣誉称号</a>	<span class="newsdate">2013-05-10</span>	</li>
	<li>[组图]我校被授予“影子教师”培训基地<span class="newsdate">2013-05-10</span></li>		
	<li>[组图]我校荣获“2010-2012年石家庄市创先争优先进基层党组织荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市妇联系统先进集体称号	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校离退休干部党支部被评为“先进离退休干部党支部”荣誉称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校获得“全国青少年普法教育先进单位”荣誉称号<span class="newsdate">2013-05-10</span></li>	
	<li>[组图]我校荣获“2010年度住房公积金管理先进单位”荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校荣获石家庄市“2010年度实绩突出领导班子”荣誉称号<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市2008—2009年度文明单位光荣称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校党委荣获2009年度先进基层党组织称号<span class="newsdate">2013-05-10</span></li>	
	<li>[组图]我校荣获首批“河北省现代教育技术示范学校”	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校被评为“首届中华百年名校”<span class="newsdate">2013-05-10</span></li>	
	<li>[图文]我校荣获石家庄市“先进基层党组织”荣誉称号	<span class="newsdate">2013-05-10</span></li>
	<li>[图文]我校荣获“2007年度实绩突出领导班子”称号<span class="newsdate">2013-05-10</span></li>	
	<li>[图文]我校荣获“2007年度民主评议工作先进单位”荣誉	<span class="newsdate">2013-05-10</span></li>
	<li>[组图]我校荣获石家庄市2008年中小学田径运动会“体育道德风尚奖”<span class="newsdate">2013-05-10</span>	</li>
	<li>[组图]我校被石家庄市委市政府评为“双争共建文明校园”	<span class="newsdate">2013-05-10</span></li>
            </ul>
            <div id="page">
	<span class="disabled">前一页</span><span class="current">1</span><a href="#?page=2">2</a><a href="#?page=3">3</a><a href="#?page=4">4</a><a href="#?page=5">5</a><a href="#?page=6">6</a><a href="#?page=2" class="disabled">后一页 
	 </a></div>
        </div>
 
      </div>
 
	<div id="foot">	  
 		Copyright © 2008－2013 http://www.***.com All Rights Reserved   网站备案：冀ICP备00000000号
	</div>
</body>
<script type="text/javascript" src="js/pic.js"></script>
</html>



index.html

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<link href="{CSS_PATH}/hbschool/erweima.css" rel="stylesheet" type="text/css" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>河北中学</title>
<link href="{CSS_PATH}/hbschool/style.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="{JS_PATH}/hbschool/jquery-1.8.2.min.js"></script>
<script type="text/javascript" src="{JS_PATH}/hbschool/solideForK13-min.js"></script>
<script type="text/javascript" src="{JS_PATH}/hbschool/ad_pic.js"></script>

</head>

<body>
	<div id="mybody">
    	<div id="top">
        	<div class="menu">
            	<ul>
                	<li>网站首页</li>


                   <!-- <li><a href="list.html">学校概况</a></li>
                    <li><a href="#">规章制度</a></li>
                    <li><a href="#">德育网</a></li>
                    <li><a href="#">教研网</a></li>
                    <li><a href="#">名师风采</a></li>
                    <li><a href="#">高考专栏</a></li>
                    <li><a href="#">图书馆</a></li>
                    <li><a href="#">校友会</a></li>
                    <li><a href="#">河中论坛</a></li>
                    <li><a href="#">查询系统</a></li>
                    <li><a href="#" class="specil">东校区</a></li>   -->   

		{pc:content action="category" catid="0" siteid="$siteid" order="listorder ASC" num="11"}
		{loop $data $v}
		<li><a href="{$v['url']}">{$v['catname']}</a></li>
		{/loop}
		{/pc}              
                </ul>
            </div>
            <div id="search">
            <input name="search" type="text" class="search_text" /><input name="searchbut" type="button" class="search_but" value=" " />
            </div>
        </div>
 <!--第一部分内容-->
        <div id="no1">
        	<div id="picnews">
            
           	 <div class="container" id="idTransformView">
  <ul class="slider" id="idSlider">
    <li><img src="{IMG_PATH}/hbschool/pic.jpg" width="280" height="210"/>
    <p>adfasdfsadf</p></li>
    <li><img src="{IMG_PATH}/hbschool/pic.jpg" width="280" height="210"/>
     <p>adfasdfsadf</p></li>
    <li><img src="{IMG_PATH}/hbschool/pic.jpg" width="280" height="210" usemap="#Map3" border="0"/>
      <map name="Map3" id="Map3">
        <area shape="rect" coords="10,62,115,164" href="#" />
      </map>
     <p>adfasdfsadf</p></li>
  </ul>
  <ul class="num" id="idNum">
    <li>1</li>
    <li>2</li>
    <li>3</li>
  </ul>
</div>
           	  <div id="news">
                   <h1><img src="{IMG_PATH}/hbschool/news_pic_title.gif" width="430" height="50" usemap="#Map2" border="0" />
                     <map name="Map2" id="Map2">
                       <area shape="rect" coords="386,21,430,44" href="{APP_PATH}index.php?m=content&c=index&a=lists&catid=25"
" />
                     </map>
                   </h1>
                   <ul >
		{pc:content action="lists" catid="25" order="inputtime DESC" num="8"}
		{loop $data $v}
		<li><a href="{$v['url']}" >{$v['title']}</a><span class="newsdate">{date('Y-m-d',$v['inputtime'])}</span></li>
		{/loop}
		{/pc}


		
           <!--         <li><a href="content.html" class="hot">【家长学校1306期】大学主要的专业介绍</a><span class="newsdate">2013-05-10</span></li>
                   	<li><a href="#" >[图文]化学老师于文英举办观摩课活动 </a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[图文]本部数学组组织公开课教学</a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[图文]生物老师开展观摩课活动</a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[图文]首届“五四杯”青年篮球对抗赛成功举办</a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[组图]校工会组织教职工广场舞展示、交流活动</a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[组图]高二理科部召开第二次月考表彰大会</a><span class="newsdate">2013-05-10</span></li>
                    <li><a href="#">[组图]加强消防培训，确保学生安全</a><span class="newsdate">2013-05-10</span></li>-->



                   </ul>
                  
                 </div>
            </div>
          <div id="notice">
          	<h1><a href="{APP_PATH}index.php?m=content&c=index&a=lists&catid=26"><img src="{IMG_PATH}/hbschool/30.gif" width="30" height="9" /></a></h1>
            <ul>

		{pc:content action="lists" catid="26" order="inputtime DESC" num="8"}
		{loop $data $v}
		<li><a href="{$v['url']}" >{$v['title']}</a><span class="newsdate">{date('Y-m-d',$v['inputtime'])}</span></li>
		{/loop}
		{/pc}


           	  <!--<li><a href="#" ><img src="{IMG_PATH}/hbschool/pot.gif" width="4" height="4" /> 河北中学男子篮球体育特长生招生简章 (2013-04-11)</a></li>
                   	<li><a href="#" ><img src="{IMG_PATH}/hbschool/pot.gif" width="4" height="4" /> 河北中学音乐特长生复试名单 (2013-04-08)</a></li>
                    <li><a href="#"><img src="{IMG_PATH}/hbschool/pot.gif" width="4" height="4" /> 河北中学2013年艺术特长生招生简章 (2013-03-01)</a></li>
                    <li><a href="#"><img src="{IMG_PATH}/hbschool/pot.gif" width="4" height="4" /> 2012-2013第二学期考试、放假安排 (2013-02-25) </a></li>-->



            </ul>
          </div>
        </div>
 <!--第二部分内容-->

	  <div id="no2">
        	<div class="news_content">
            	<h1><img src="{IMG_PATH}/hbschool/news_jy_title.gif" width="480" height="40" usemap="#Map" border="0" alt="教研网" />
                  <map name="Map" id="Map">
                    <area shape="rect" coords="439,11,481,33" href="{APP_PATH}index.php?m=content&c=index&a=lists&catid=17"" />
                  </map>
            	</h1>
         		<img src="{IMG_PATH}/hbschool/news_jy_pic.gif" width="130" height="165" alt="tp" />
                 <ul>
		{pc:content action="lists" catid="17" order="inputtime DESC" num="8"}
		{loop $data $v}
		<li><a href="{$v['url']}" >{$v['title']}</a><span class="newsdate">{date('Y-m-d',$v['inputtime'])}</span></li>
		{/loop}
		{/pc}                	



				<!--<li><a href="#">[公开课教学][图文]化学老师于文英举办观摩课活动</a> </li> 
					<li><a href="#">[公开课教学][图文]本部数学组组织公开课教学校调研 </a> </li> 
					<li><a href="#">[公开课教学][图文]生物老师开展观摩课活动</a> </li>  
 					<li><a href="#">[教学交流][组图]文科部高一年级召开期中考试分析…</a> </li>  
					<li><a href="#">[教与学][图文]【教与学】打破思维定势走出误区…</a> </li>  
 					<li><a href="#">[教学交流][组图]石家庄市教科所专家来我</a> </li> -->
                </ul>
          </div>
            <div class="news_content" style="margin-left:45px; _margin-left:25px">
            	<h1><img src="{IMG_PATH}/hbschool/news_dy_title.gif" width="480" height="40" usemap="#Map" border="0" alt="教研网" />
                  <map name="Map" id="Map">
                    <area shape="rect" coords="439,11,481,33" href="{APP_PATH}index.php?m=content&c=index&a=lists&catid=16"" />
                  </map>
            	</h1>
         		<img src="{IMG_PATH}/hbschool/news_dy_pic.gif" width="130" height="165" alt="tp" />
                <ul>
		{pc:content action="lists" catid="16" order="inputtime DESC" num="8"}
		{loop $data $v}
		<li><a href="{$v['url']}" >{$v['title']}</a><span class="newsdate">{date('Y-m-d',$v['inputtime'])}</span></li>
		{/loop}
		{/pc}


                	<!--<li><a href="#">[公开课教学][图文]化学老师于文英举办观摩课活动</a> </li> 
					<li><a href="#">[公开课教学][图文]本部数学组组织公开课教学校调研 </a> </li> 
					<li><a href="#">[公开课教学][图文]生物老师开展观摩课活动</a> </li>  
 					<li><a href="#">[教学交流][组图]文科部高一年级召开期中考试分析…</a> </li>  
					<li><a href="#">[教与学][图文]【教与学】打破思维定势走出误区…</a> </li>  
 					<li><a href="#">[教学交流][组图]石家庄市教科所专家来我</a> </li> -->
                </ul>
            </div>
          </div>
 <!--第三部分内容-->  
 			
 <!--第四部分内容-->
      <div id="no4">
      	<div id="synopsis">
   	     <img src="{IMG_PATH}/hbschool/gnq.gif" width="258" height="260" usemap="#Map4" style="margin-top:10px;" border="0"/>
         <map name="Map4" id="Map4">
           <area shape="rect" coords="144,133,250,240" href="成绩查询" />
           <area shape="rect" coords="12,129,119,239" href="通讯录" />
           <area shape="rect" coords="9,6,116,113" href="视频" />
           <area shape="rect" coords="140,9,243,114" href="班级空间" />
         </map>
        </div>
        <div id="slide_1">
		<div class="slide_content">
			<ul>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
			  </li>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
				</li>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
				</li>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
				</li>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
				</li>
				<li>					
					<a href="#"><img src="{IMG_PATH}/hbschool/tup.gif" alt=""></a>
					<p>校园美景</p>
				</li>			
			</ul>
		</div>
		<ul class="index_name"></ul>		
	    </div>
      </div>

     </div>    
<div id="foot">	
  <div id="nr">
    	<div class="foot_link" >
        	<h1><img src="{IMG_PATH}/hbschool/foot_link.gif" width="150" height="36" alt="友情链接" /></h1>
            <ul >
            	<li><a href="#">邯郸市第一中学的网站</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a>          </li>
            </ul >
    	</div>
    	<div class="foot_link" >
        	<h1><img src="{IMG_PATH}/hbschool/foot_school.gif" width="150" height="36" alt="友情链接" /></h1>
            <ul >
            	<li><a href="#">邯郸市第一中学的网站</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
                <li><a href="#">邯郸市第一中学</a></li>
            </ul >
           
   	      </div>
          
          <div class="foot_link">
        	<h1><img src="{IMG_PATH}/hbschool/foot_down.gif" width="150" height="36" alt="资源下载" /></h1>
            <ul>
            	<li><a href="#">[资源中心]教师班主任成绩公示系统</a></li>
                <li><a href="#">[资源中心]高考资源网</a></li>
                <li><a href="#">[资源中心]中学学科网系统</a></li>
                <li><a href="#">[资源中心]全品高考网</a></li>
                <li><a href="#">[资源中心]志鸿网园校办公系统</a></li>
            </ul>            
   	      </div>
          
              <div class="foot_link" style="margin-right:0">
        	<h1><img src="{IMG_PATH}/hbschool/foot_count.gif" width="150" height="36" alt="网站统计" /></h1>
            <ul>
            	<li>总访问量：2600700</li>
                <li>人总浏览量：3482048人</li>
                <li>今日访问：2506人</li>
                <li>日均访问：1653人</li>
                <li>当前在线：21人</li>
            </ul>            
   	      </div>
  </div>
  <div id="copyright">Copyright © 2008－2013 http://www.***.com All Rights Reserved   网站备案：冀ICP备00000000号</div>
</div>
	  <div id="erweima">

	  </div>
	  <div id="qqweibo">
		<img src="{IMG_PATH}/hbschool/qq.gif" /><br />
		<img src="{IMG_PATH}/hbschool/weibo.gif" />
	  </div>
	  <script type="text/javascript">
		$("#close").click(function(){
			$(this).parent().css("display",'none');
		});
	  </script>
</body>

</html>
