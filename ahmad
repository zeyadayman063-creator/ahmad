<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>منصتي التعليمية</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background: linear-gradient(135deg,#0f172a,#111827,#1e293b);
    color:white;
}

/* Navbar */
nav{
    background:#0b1120;
    padding:15px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:999;
    box-shadow:0 0 20px rgba(0,0,0,.5);
}

.logo{
    font-size:24px;
    font-weight:bold;
    color:#38bdf8;
}

/* Hero */
.hero{
    text-align:center;
    padding:50px 20px;
}

.hero h1{
    font-size:40px;
    margin-bottom:10px;
}

.hero p{
    color:#cbd5e1;
}

/* Cards */
.container{
    width:90%;
    margin:auto;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:20px;
    padding:30px 0;
}

.card{
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.1);
    border-radius:20px;
    padding:20px;
    transition:.3s;
    backdrop-filter: blur(10px);
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 0 25px rgba(56,189,248,.4);
}

.card h2{
    margin-bottom:10px;
    color:#38bdf8;
}

.card p{
    color:#cbd5e1;
    margin-bottom:15px;
}

.card button{
    width:100%;
    padding:12px;
    border:none;
    border-radius:12px;
    background:#38bdf8;
    color:black;
    font-weight:bold;
    cursor:pointer;
    transition:.3s;
}

.card button:hover{
    background:white;
}

/* Footer */
footer{
    text-align:center;
    padding:25px;
    background:#0b1120;
    margin-top:30px;
}

footer p{
    color:#94a3b8;
}

@media(max-width:700px){
    .hero h1{
        font-size:30px;
    }

    nav{
        flex-direction:column;
        gap:15px;
    }
}
</style>
</head>

<body>

<!-- Navbar -->
<nav>
    <div class="logo">✨Ahmad Osama✨</div>
</nav>

<!-- Hero -->
<section class="hero" id="home">
    <h1>لكل الطلاب الأعزاء لمستر أحمد</h1>
    <p>
        ✨ منصة تعليمية لتسهيل الدراسة 📚
        فيديوهات 💾 + ملفات PDF 🖨️ + امتحانات 📝
    </p>
</section>

<!-- Sections -->
<div class="container">

    <!-- الاشتراك -->
    <div class="card" id="courses">
        <h2>اشترك الان</h2>
        <p>
            بعد الاشتراك هتاخد ID وتقدر تدخل علي الفيديوهات 💾
            وتستلم PDF 📘 وتمتحن 📝
        </p>

        <button onclick="window.open('https://wa.me/201152711536','_blank')">
            دخول القسم
        </button>
    </div>

    <!-- الامتحانات -->
    <div class="card" id="exams">
        <h2>الامتحانات</h2>
        <p>امتحان بـ ID ودرجة لمعرفة مستواك</p>
    </div>

    <!-- النتيجة -->
    <div class="card" id="results">
        <h2>النتيجة</h2>
        <p>تيم الدعم هيبعت النتيجة 📞</p>
    </div>

    <!-- الدعم -->
    <div class="card" id="support">
        <h2>الدعم الفني</h2>
        <p>اكتب مشكلتك وسيتم الرد عليك على واتساب</p>

        <button onclick="supportToWhatsApp()">
            تواصل
        </button>
    </div>

</div>

<footer>
    <p>© جميع الحقوق محفوظة - منصة مستر أحمد</p>
</footer>

<script>
function supportToWhatsApp(){
    let msg = prompt("اكتب مشكلتك هنا 👇");

    if(msg && msg.trim() !== ""){
        let phone = "201152711536";
        let url = "https://wa.me/" + phone + "?text=" + encodeURIComponent(msg);
        window.open(url, "_blank");
    } else {
        alert("من فضلك اكتب المشكلة أولاً");
    }
}
</script>

</body>
</html>
