/// Code for the QR code hub challenge


!!HTML!!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qr</title>
    <link rel="stylesheet" href="qr.css">
</head>
<body>
    <section class="wrapper">
        <div class="img">
        <img src="image-qr-code.png">
        </div>
        <div>
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding to the next level</p>
    </div>
    </section>
    
</body>
</html>




!!CSS!!

body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 0;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    background-color: #d5e1ef;
    height: 100svh;
    font-family: sans-serif;
}
.wrapper{
    border-radius: 20px;
    max-width: 40vh;
    border: 3px black;
    background-color: #fffcff;
    box-shadow: 15px 10px 5px rgba(199, 194, 194, 0.144);
    padding-top: 20px;
    padding-left: 20px;
    padding-right: 20px;
}
.img img{
    overflow: hidden;
    max-width: 40vh;
    border-radius: 15px;
}
h1{
    font-size: xx-large;
}
p{
font-size: larger;
padding-bottom: 25px;
color: #b8b5b8;
}
