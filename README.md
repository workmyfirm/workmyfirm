<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WORKMYFIRM</title>

<style>
body {
    margin:0;
    font-family: 'Segoe UI', sans-serif;
}

/* Navbar */
nav {
    display:flex;
    justify-content:space-between;
    padding:15px 30px;
    background:#0a3d62;
    color:white;
}

nav a {
    color:white;
    margin-left:20px;
    text-decoration:none;
    font-weight:bold;
}

/* Hero */
.hero {
    background:linear-gradient(to right,#0a3d62,#38ada9);
    color:white;
    text-align:center;
    padding:90px 20px;
}

.hero h1 {
    font-size:42px;
}

.btn {
    background:#27ae60;
    padding:12px 25px;
    color:white;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

/* Section */
.section {
    padding:60px 20px;
    text-align:center;
}

.services {
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card {
    background:#f4f4f4;
    padding:25px;
    border-radius:12px;
    transition:0.3s;
    font-weight:bold;
}

.card:hover {
    transform:scale(1.05);
}

/* Contact */
.contact {
    background:#0a3d62;
    color:white;
}

/* Footer */
footer {
    background:#222;
    color:white;
    padding:15px;
    text-align:center;
}

/* WhatsApp Button */
.whatsapp {
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-size:20px;
}
</style>

</head>

<body>

<nav>
<div><b>WORKMYFIRM</b></div>
<div>
<a href="#">Home</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</div>
</nav>

<section class="hero">
<h1>Smart Solutions For Bold Businesses</h1>
<p>Loan | Insurance | Taxation | Investment | Marketing | HR | Real Estate</p>
<br>
<a href="https://wa.me/message/WWGBOBSDIHA7O1" class="btn">Get Free Consultation</a>
</section>

<section class="section">
<h2>About Us</h2>
<p>WORKMYFIRM provides smart and reliable business solutions across India. We help businesses grow with expert support.</p>
</section>

<section class="section" id="services">
<h2>Our Services</h2>

<div class="services">
<div class="card">Loan Services</div>
<div class="card">Insurance</div>
<div class="card">Taxation</div>
<div class="card">Investment</div>
<div class="card">Marketing</div>
<div class="card">Human Resource</div>
<div class="card">Real Estate</div>
</div>

</section>

<section class="section">
<h2>Why Choose Us</h2>
<p>✔ Expert Team | ✔ Fast Processing | ✔ Trusted Service | ✔ Pan India</p>
</section>

<section class="section contact" id="contact">
<h2>Contact Us</h2>
<p>
