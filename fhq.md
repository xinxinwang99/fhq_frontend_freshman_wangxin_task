~~~
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

li {
    list-style: none;
}

body {
    font: 14px/1.5 "Microsoft YaHei", "微软雅黑", Arial, Helvetica, sans-serif;
    color: #d4d1e4;
    overflow: hidden;
}

a {
    color: #bab8d3;
    text-decoration: none;
}

~~~





~~~

.container{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100%;
    background-image: url(/image/preview.jpg);
    background-size: cover;
    
}

.parent{
    width: 80%;
    height: 90%;
    /* background-color: aliceblue; */
    margin: 30px auto;
    border: 3px solid rgba(6, 6, 46, 0.5);
    border-radius: 10px;
    box-shadow: 10px 10px 10px rgba(10, 10, 50, 0.5);
    background-image: url(/image/zhong.jpg);
    /* background: linear-gradient(rgba(255, 255, 255, 0.5), rgba(65, 60, 90, 0.1)), url('/image/zhong.jpg'); */
    background-size: cover;
    opacity: 0.7;
}

.content {
    /* opacity: 0; */
    display: none;
}

.parent .nav {
    display: flex;
    justify-content: space-around;
    height: 100px;
    margin-top: 10px;
    /* filter: opacity(0.); */
}

.parent .nav .heart {
    background-color: aquamarine;
    height: 100px;
    width: 100px;
}

.parent .nav h1{
    display: block;
    font-size: 40px;
    margin-left: 50px;
    line-height: 100px;
    
}

.parent .nav ul{
    display: flex;
    align-items: center;
}

.parent .nav ul li{
    margin-right: 20px;
    margin-left: 20px;
    font-size: 20px;
    font-weight: 900;
    text-transform: uppercase;
}

.parent .nav ul li :last-child {
    margin-right: 60px;
}

.parent .nav ul li a:hover{
    color: rgb(255, 255, 255);
}


.parent .left {
    font-size: large;
    margin: 90px;
    width: 300px;
}

.parent .left h1{
    display: block;
    width: 190px;
    text-transform: uppercase;
    font-size: 38px;
    color: rgb(100, 100, 232);
}

.parent .left h2{
    font-size: 25px;
    margin-top: 30px;
    margin-bottom: 15px;
}

button {

    width: 140px;
    height: 30px;
    margin-top: 15px;
    border-radius: 11px;
    font-size: 18px;
    border: none;
    color: rgb(218, 218, 234);
    background-color: transparent;
    text-transform: uppercase;
    cursor: pointer; /* Change cursor to pointer on hover */
}

button:hover {
    background-color: rgba(255, 255, 255, 0.5);
}

.content1 {
    /* background-color: aqua; */
    width: 1100px;
    height: 600px;
    margin: auto;
    display: none;
}

.content1 .top {
    width: 100%;
    height: 85%;
    /* background-color: blue; */
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.content1 .bottom {
    width: 100%;
    height: 15%;
    /* background-color: brown; */
}

.first_content{
    width: 160px;
    height: 190px;
    margin: 35px;
    /* background-color: red; */
    border: 0px solid rgb(255, 255, 255);
    box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
    border-radius: 10px;
}

.first_content .img_box img {
    object-fit: cover;
}

.first_content img {
    width: 100%;
}

.first_content p {
    font-size: 32px;
    text-align: center;
    color: rgb(54, 86, 169);
}

.bottom {
    text-align: center;
}

.bottom button {
    height: 30px;
    width: 30px;
    background-color: rgb(25, 25, 181);
    margin: 25px 7px;
    cursor: pointer;
}

.content2 {
    /* background-color: aqua; */
    width: 80%;
    height: 80%;
    margin: auto;
    display: none;
}

.content2 {
    /* display: flex; */
    justify-content: center;
    text-align: center;
    position: relative;
}


.item {
    line-height: 300px;
    position: absolute;
    width: 400px;
    height: 300px;
    background-color: aliceblue;
    top: 30%;
    left: 31%;
    transition: 0.5s;
    user-select: none;
    /* 这段CSS代码的作用是禁止用户在网页上选择文本或元素。它使得页面中的文本无法被高亮选中 */
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 5em;
    font-family: consolas;
    font-weight: 800;
    color: rebeccapurple;
    box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
    opacity: 0;
}

.active {
    display: block !important;
}

.item:nth-child(1){
    transform: translate3d(-250px,0,0) scale(0.8);
    opacity: 1;
    z-index: 1;
    background-color: #402f89;
}

.item:nth-child(2){
    transform: translate3d(-300px,0,0) scale(0.8);
    opacity: 1;
    z-index: 2;
    background-color: #8b2e2e;
}
.item:nth-child(3){
    transform: translate3d(-150px,0,0) scale(0.9);
    opacity: 1;
    z-index: 3;
    background-color: #235e4c;
}

.item:nth-child(4){
    transform: translate3d(0px,0,0) scale(1);
    opacity: 1;
    z-index: 4;
    background-color: #d2deda;
}

.item:nth-child(5){
    transform: translate3d(150px,0,0) scale(0.9);
    opacity: 1;
    z-index: 3;
    background-color: #243f36;
}

.item:nth-child(6){
    transform: translate3d(300px,0,0) scale(0.8);
    opacity: 1;
    z-index: 2;
    background-color: #2b6954;
}

.item:nth-child(7){
    transform: translate3d(300px,0,0) scale(0.8);
    opacity: 1;
    z-index: 1;
    background-color: #0f211b;
}

~~~

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>study_note</title>
    <link rel="stylesheet" href="css/base.css">
    <link rel="stylesheet" href="css/index.css"></link>
</head>
<body>
    <div class="container">
        <div class="parent">
            <div class="nav">
                <h1>writer  某炘炘</h1>
                <ul><li class="home"><a href="#">home</a></li>
                    <li class="note"><a href="#">note</a></li>
                    <li class="memory"><a href="#">memory</a></li>
                    .
                </ul>
            </div>
            <div class="content">
                <div class="left">
                    <h1><span>My Own Last Space</span></h1>
                    <h2>here help yourself!</h2>
                    <div class="left_content">
                        <p>You stop behaving like the world is out to get you，when it is so clearly dropping gifts at your feet.</p>
                    </div>
                    <button type="submit"><a href="note.md">start</a></button>
                </div>
            </div>


            <div class="content1">
                <div class="top">
                    <!-- 因为前期还没有足够素材可以需要用到javascript，所以暂时没有写 -->
                    <div class="first_content">
                        <div class="img_box">
                            <a href="笔记/html_study.md"><img src="image/a1.png" alt=""></a>
                        </div>
                        <p><a href="笔记/html_study.md">html</a></p>
                    </div>
                    <div class="first_content">
                        <div class="img_box">
                            <a href="笔记/css_study.md"><img src="image/a2.png" alt=""></a>
                        </div>
                        <p><a href="笔记/css_study.md">css</a></p>
                    </div>
                    <div class="first_content"></div>
                    <div class="first_content"></div>
                    <div class="first_content"></div>
                    <div class="first_content"></div>
                    <div class="first_content"></div>
                    <div class="first_content"></div>
                </div>
                <div class="bottom">
                    <button class="prev">&lt;</button>
                    <button class="next">&gt;</button>
                </div>
            </div>

            <div class="content2 active">   
            </div>
            <script>
                parent = document.querySelector('.parent')
                content = document.querySelector('.content');
                content1 = document.querySelector('.content1');
                liHome = document.querySelector('.nav ul .home');
                liNote = document.querySelector('.nav ul .note');
                liMemory = document.querySelector('.nav ul .memory');
                liTool = document.querySelector('.nav ul .tool');
                liHome.addEventListener('click',function(){
                    active = document.querySelector('.active')
                    active.classList.remove('active')
                    content.classList.add('active')
                })
                liNote.addEventListener('click',function(){
                    active = document.querySelector('.active')
                    active.classList.remove('active')
                    content1.classList.add('active')
                })
                liMemory.addEventListener('click',function(){
                    active = document.querySelector('.active')
                    active.classList.remove('active')
                    content2.classList.add('active')
                })
                // liTool.addEventListener('click',function(){


                // })

                let content2 = document.querySelector('.content2')
                let urls = [
                    'image/02.jpg',
                    'image/03.jpg',
                    'image/04.jpg',
                    'image/05.jpg',
                    'image/06.jpg',
                    'image/07.jpg',
                    'image/08.jpg',
                    'image/09.jpg',
                    'image/10.jpg',
                    'image/11.jpg',
                    'image/12.jpg',
                    'image/13.jpg',
                    'image/14.jpg',

                ]
                for(let i = 0;i<100;i++) {
                    let div = document.createElement('div')
                    div.className = 'item'
                    div.textContent = i
                    content2.appendChild(div)
                    div.style.backgroundImage = `url(./image/${i}.jpg)`
                    div.style.backgroundSize = 'cover'
                }


                function moveNext() {
                    let items = document.querySelectorAll('.item')
                    content2.appendChild(items[0])
                }
                function movePrev() {
                    let items = document.querySelectorAll('.item')
                    content2.prepend(items[items.length - 1])
                }

                window.addEventListener('wheel',function(e) {
                    if(e.deltaY > 0) {
                        moveNext()
                    } else {
                        movePrev()
                    }
                })



            </script>
        </div>
    </div>
</body>
</html>
~~~


