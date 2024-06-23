<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>主内应用</title>
    <style>
        @media (min-width: 320px) {
            .layout { width: 100%; }
            .box { width: 90%; }
            .button2 { width: 48%; }
        }
        @media (min-width: 480px) {
            .layout { width: 100%; }
            .box { width: 80%; }
            .button2 { width: 48%; }
        }
        @media (min-width: 720px) {
            .layout { width: 50%; float:left; }
            .box { width: 80%; }
            .button2 { width: 100%; }
        }
        @media (min-width: 960px) {
            .layout { width: 50%; float:left; }
            .box { width: 80%;}
            .button2 { width: 100%; }
        }
        .container {
            background-color: #f0f0f0;
            padding: 2% 5%;
            border-radius: 10px;
            margin: 10px auto;
        }
        .container1 {
            background-color: #ac92ec;
        }
        .container2 {
            background-color: #1abc9c;
        }

        h1 {
            color: white
        }

        .button {    
            background-color: #4CAF50; /* Green */    
            border: none;    
            color: white;    
            padding: 16px 32px;    
            text-align: center;    
            text-decoration: none;    
            font-size: 20px;
            display: inline-block;    
            margin: 4px 2px;    
            -webkit-transition-duration: 0.4s; /* Safari */    
            transition-duration: 0.4s;    
            cursor: pointer;
        } 
        .button1 {    
            background-color: white;     
            color: black;     
            border: 2px solid #008CBA;
        } 
        .button1:hover {    
            background-color: #008CBA;    
            color: white;
        } 
        
        </style>
</head>
<body>
    <div class="layout">
        <div class="container container1 box">
            <h1>精读圣经</h1>
            <button class='button button1 button2' onclick="window.location.href='https://a1189.icu/#/bible'">站点一</button>
            <button class='button button1 button2' onclick="window.location.href='https://appkpj.icu/#/bible'">问题反馈请加qq号727546069</button>
        </div>
    </div>
    <div class="layout">
        <div class="container container2 box">
            <h1>诗歌本</h1>
            <button class='button button1 button2' onclick="window.location.href='https://a1189.icu/#/hymn'">站点一</button>
            <button class='button button1 button2' onclick="window.location.href='诗歌本.apk'">本站下载</button>
            <button class='button button1 button2' onclick="window.location.href='https://appkpj.icu/#/hymn'">问题反馈请加qq号727546069</button>
        </div>
    </div>    
</body>
