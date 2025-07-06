<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>KPM Desa Seda</title>
<!-- Font Awesome untuk ikon -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
<style>
  body {
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    background-color: #f0f0f0;
  }

  /* Header atas dengan logo dan menu */
  .header-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .header-left {
    display: flex;
    align-items: center;
    gap: 20px;
  }
  .header-left div {
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .header-left i {
    font-size: 16px;
    color: #333;
  }
  select {
    padding: 4px 8px;
  }

  /* Logo dan judul */
  .logo-section {
    display: flex;
    align-items: center;
    padding: 20px;
  }
  .logo-container {
    display: flex;
    align-items: center;
    background-color: #fff;
    padding: 10px 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .logo-container img {
    width: 76px;
    height: auto;
    margin-right: 15px;
    border-radius: 8px;
  }
  .logo-container h2 {
    margin: 0;
  }

  /* Menu Navigasi */
  nav.menu {
    background-color: #fff;
    display: flex;
    justify-content: center;
    padding: 10px 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    font-weight: 600;
  }
  nav.menu a {
    margin: 0 20px;
    text-decoration: none;
    color: #000;
  }
  nav.menu a:hover {
    color: #0693e3;
  }

  /* Bagian ikon dan judul */
  .icons-section {
    display: flex;
    gap: 20px;
    justify-content: center;
    padding: 30px 20px;
    background-color: #fff;
  }
  .icon-box {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 150px;
    padding: 20px;
    background-color: #f7f7f7;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .icon-box i {
    font-size: 40px;
    margin-bottom: 10px;
    color: #006400; /* hijau gelap */
  }
  .icon-box span {
    font-weight: bold;
    text-align: center;
  }

  /* Bagian bawah berwarna biru dan hijau */
  .bottom-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 40px 20px;
    background-color: #0066cc; /* biru */
    color: #fff;
  }
  .bottom-box {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 200px;
    margin: 20px;
  }
  .bottom-box i {
    font-size: 40px;
    margin-bottom: 10px;
  }
  .bottom-box h4 {
    margin: 10px 0 5px 0;
  }

  /* Responsif */
  @media(max-width: 768px){
    .icons-section {
      flex-direction: column;
      align-items: center;
    }
    .bottom-section {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
</head>
<body>

<!-- Header atas -->
<div class="header-top">
  <div class="header-left">
    <div><i class="fas fa-envelope"></i> sipp@ui.ac.id dan humas-ui@ui.ac.id</div>
    <div><i class="fas fa-phone"></i> +62 21 786 7222</div>
  </div>
  <div>
    <select>
      <option>INDONESIA</option>
      <option>ENGLISH</option>
    </select>
  </div>
</div>

<!-- Logo dan Judul -->
<div class="logo-section">
  <div class="logo-container">
    <img src="https://via.placeholder.com/76" alt="Logo Desa Seda" />
    <h2>KPM Desa Seda</h2>
  </div>
</div>

<!-- Menu Navigasi -->
<nav class="menu">
  <a href="#">BERITA</a>
  <a href="#">PROFIL</a>
  <a href="#">KINERJA</a>
  <a href="#">LAYANAN</a>
  <a href="#">TRANSFORMASI DIGITAL</a>
  <a href="#">INFORMASI PUBLIK</a>
</nav>

<!-- Ikon dan Judul -->
<div class="icons-section">
  <div class="icon-box">
    <i class="fas fa-sitemap"></i>
    <span>Struktur Organisasi</span>
  </div>
  <div class="icon-box">
    <i class="fas fa-bullseye"></i>
    <span>VISI MISI</span>
  </div>
  <div class="icon-box">
    <i class="fas fa-briefcase"></i>
    <span>PROGRAM KERJA</span>
  </div>
  <div class="icon-box">
    <i class="fas fa-file-alt"></i>
    <span>LAPORAN</span>
  </div>
</div>

<!-- Bagian bawah berwarna biru -->
<div class="bottom-section">
  <div class="bottom-box">
    <i class="fas fa-sitemap"></i>
    <h4>Struktur Organisasi</h4>
    <p>Selengkapnya</p>
  </div>
  <div class="bottom-box">
    <i class="fas fa-bullseye"></i>
    <h4>VISI MISI</h4>
    <p>Selengkapnya</p>
  </div>
  <div class="bottom-box">
    <i class="fas fa-briefcase"></i>
    <h4>PROGRAM KERJA</h4>
    <p>Selengkapnya</p>
  </div>
  <div class="bottom-box">
    <i class="fas fa-file-alt"></i>
    <h4>LAPORAN</h4>
    <p>Selengkapnya</p>
  </div>
</div>

</body>
</html>
