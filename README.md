# omar-yara-invitation

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yara & Omar | Engagement</title>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Great+Vibes&display=swap" rel="stylesheet">

<style>
* { box-sizing: border-box; }

body {
  margin: 0;
  background: #f8f3eb;
  color: #786044;
  font-family: 'Cormorant Garamond', serif;
  text-align: center;
}

.page {
  max-width: 520px;
  min-height: 100vh;
  margin: auto;
  padding: 28px 22px 45px;
  border: 1px solid #d6bd8a;
  outline: 5px solid #f8f3eb;
  background: linear-gradient(160deg, #fffdf8, #f5ecdd);
}

.eyebrow {
  letter-spacing: 4px;
  font-size: 12px;
  margin-top: 24px;
}

h1 {
  font-family: 'Great Vibes', cursive;
  font-size: clamp(48px, 12vw, 68px);
  font-weight: 400;
  margin: 22px 0 4px;
  color: #a7834e;
}

.amp {
  font-family: 'Cormorant Garamond', serif;
  font-size: 28px;
  font-style: italic;
}

.subtitle {
  letter-spacing: 3px;
  font-size: 13px;
  margin: 24px 0;
}

.photo {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border: 1px solid #c9ab75;
  padding: 5px;
  background: white;
}

.photo-placeholder {
  width: 100%;
  height: 300px;
  border: 1px solid #c9ab75;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 25px;
  color: #a7834e;
  letter-spacing: 2px;
  font-size: 13px;
}

.date-heart {
  margin: 28px auto 10px;
  width: 190px;
  height: 115px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

.heart {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
}

.date-text {
  position: relative;
  z-index: 1;
  font-size: 19px;
  letter-spacing: 2px;
  line-height: 1.5;
}

.section {
  border-top: 1px solid #ddcba9;
  margin-top: 26px;
  padding-top: 22px;
}

.section h2 {
  font-weight: 500;
  letter-spacing: 3px;
  font-size: 18px;
}

.details {
  font-size: 20px;
  line-height: 1.8;
}

#countdown {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin: 20px 0;
}

.time {
  min-width: 62px;
  padding: 12px 5px;
  border: 1px solid #d6bd8a;
}

.time strong {
  display: block;
  font-size: 25px;
  font-weight: 500;
}

.time span {
  font-size: 10px;
  letter-spacing: 1px;
}

input, textarea {
  width: 100%;
  padding: 13px;
  margin: 8px 0;
  background: #fffdf8;
  border: 1px solid #d6bd8a;
  color: #786044;
  font-family: inherit;
  font-size: 17px;
}

textarea {
  min-height: 90px;
  resize: vertical;
}

button {
  background: #a7834e;
  color: white;
  border: none;
  padding: 13px 22px;
  margin-top: 8px;
  font-family: inherit;
  font-size: 16px;
  letter-spacing: 1px;
  cursor: pointer;
}

button:hover { background: #80613b; }

.music-note {
  font-size: 13px;
  line-height: 1.7;
}

footer {
  margin-top: 35px;
  font-family: 'Great Vibes', cursive;
  font-size: 32px;
  color: #a7834e;
}

</style>
</head>

<body>
<main class="page">

  <p class="eyebrow">A SPECIAL DAY · A BEAUTIFUL BEGINNING</p>

  <p class="subtitle">TOGETHER WITH OUR FAMILIES</p>

  <h1>Yara <span class="amp">&</span> Omar</h1>

  <p class="subtitle">INVITE YOU TO CELEBRATE THEIR ENGAGEMENT</p>

  <!-- To add your photo, replace this placeholder with:
  <img class="photo" src="couple.jpg" alt="Yara and Omar">
  Upload couple.jpg into the same GitHub repository. -->

  <div class="photo-placeholder">
    YOUR PHOTO HERE ♡<br>
    Upload your picture to add it to the invitation
  </div>

  <div class="date-heart">
    <svg class="heart" viewBox="0 0 200 120" fill="none"
         xmlns="http://www.w3.org/2000/svg">
      <path d="M100 108 C82 90 12 53 12 29 C12 2 47 0 100 40 C153 0 188 2 188 29 C188 53 118 90 100 108Z"
        stroke="#b99a65" stroke-width="1.5"/>
    </svg>
    <div class="date-text">
      24 NOVEMBER<br>
      <span style="font-size:13px;letter-spacing:3px">2026</span>
    </div>
  </div>

  <div class="details">
    TUESDAY · 8:00 PM<br>
    PORTSAID<br>
    EL BATROS GARDEN
  </div>

  <div class="section">
    <h2>COUNTING DOWN TO OUR DAY</h2>
    <div id="countdown">
      <div class="time"><strong id="days">00</strong><span>DAYS</span></div>
      <div class="time"><strong id="hours">00</strong><span>HOURS</span></div>
      <div class="time"><strong id="minutes">00</strong><span>MINUTES</span></div>
      <div class="time"><strong id="seconds">00</strong><span>SECONDS</span></div>
    </div>
    <p id="countdown-message"></p>
  </div>

  <div class="section">
    <h2>DRESS CODE</h2>
    <div class="details">
      LADIES · BROWN<br>
      GENTLEMEN · BLACK
    </div>
  </div>

  <div class="section">
    <h2>GUEST BOOK</h2>
    <p>Please enter your name and leave us a wish.</p>

    <input id="guestName" type="text" placeholder="Your Full Name">

    <textarea id="wish" placeholder="Write your wishes for Yara & Omar..."></textarea>

    <button onclick="sendWish()">SEND YOUR WISH ♡</button>
    <p class="music-note" id="wishMessage"></p>
  </div>

  <div class="section">
    <h2>OUR SONG</h2>
    <p class="music-note">A little melody for our special day ♡</p>

    <!-- Upload song.mp3 to the same repository -->
    <audio id="song" controls loop style="width:100%">
      <source src="song.mp3" type="audio/mpeg">
      Your browser does not support audio.
    </audio>
    <p class="music-note">
      Add your chosen music file as <b>song.mp3</b> in your repository.
      Tap play to listen.
    </p>
  </div>

  <footer>With love, Yara & Omar</footer>

</main>

<script>
function updateCountdown() {
  // 8:00 PM in Port Said, Egypt (UTC+2 on this date)
  const eventDate = new Date("2026-11-24T20:00:00+02:00");
  const now = new Date();
  const diff = eventDate - now;

  if (diff <= 0) {
    document.getElementById("countdown").style.display = "none";
    document.getElementById("countdown-message").textContent =
      "Today is our special day! ♡";
    return;
  }

  document.getElementById("days").textContent =
    Math.floor(diff / 86400000);
  document.getElementById("hours").textContent =
    Math.floor((diff % 86400000) / 3600000);
  document.getElementById("minutes").textContent =
    Math.floor((diff % 3600000) / 60000);
  document.getElementById("seconds").textContent =
    Math.floor((diff % 60000) / 1000);
}

updateCountdown();
setInterval(updateCountdown, 1000);

function sendWish() {
  const name = document.getElementById("guestName").value.trim();
  const wish = document.getElementById("wish").value.trim();

  if (!name || !wish) {
    document.getElementById("wishMessage").textContent =
      "Please enter your name and your wish first.";
    return;
  }

  const message =
    "Engagement wishes for Yara & Omar 💍%0A" +
    "Guest: " + encodeURIComponent(name) + "%0A" +
    "Wish: " + encodeURIComponent(wish);

  // Replace the number below with your WhatsApp number,
  // including the country code, without the + sign.
  const whatsappNumber = "201000000000";

  if (whatsappNumber === "201000000000") {
    document.getElementById("wishMessage").textContent =
      "To receive wishes, replace the sample WhatsApp number in the code with your own number.";
    return;
  }

  window.open(
    "https://wa.me/" + whatsappNumber + "?text=" + message,
    "_blank"
  );
}
</script>

</body>
</html>
