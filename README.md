<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume – Kobe Bryant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
        }
        h1 { color: #333; }
        h2 { color: #555; border-bottom: 2px solid #552583; padding-bottom: 5px; }
        .contact { margin-bottom: 20px; }
        .section { margin-bottom: 30px; }
        .job, .education { margin-bottom: 15px; }
        strong { color: #333; }

        /* Photo layout */
        .header {
            display: flex;
            align-items: flex-start;
            gap: 30px;
            margin-bottom: 10px;
        }
        .header-text { flex: 1; }
        .profile-photo {
            width: 140px;
            height: 170px;
            object-fit: cover;
            object-position: top center;
            border-radius: 6px;
            border: 2px solid #ddd;
            flex-shrink: 0;
        }
        .photo-placeholder {
            width: 140px;
            height: 170px;
            background: #e9e9e9;
            border-radius: 6px;
            border: 2px solid #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            color: #999;
            text-align: center;
            flex-shrink: 0;
        }
    </style>
</head>
<body>

    <!-- Header with photo -->
    <div class="header">
        <div class="header-text">
            <h1>Kobe Bryant</h1>
            <div class="contact">
                <p>Email: blackmamba@nba.com | Phone: (215) 000-2408 | Location: Los Angeles, California</p>
            </div>
        </div>
        <img
            class="profile-photo"
            src="https://cdn.nba.com/headshots/nba/latest/1040x760/977.png"
            alt="Kobe Bryant"
            onerror="this.style.display='none'; document.getElementById('photo-fallback').style.display='flex';"
        />
        <div class="photo-placeholder" id="photo-fallback" style="display:none;">
            Photo<br>unavailable
        </div>
    </div>

    <div class="section">
        <h2>Summary</h2>
        <p>Elite professional basketball player with 20 seasons in the NBA, all with the Los Angeles Lakers. 5× NBA Champion and 18× All-Star widely regarded as one of the greatest players in basketball history. Renowned for an unmatched competitive drive, technical mastery, and the "Mamba Mentality" philosophy of relentless self-improvement and excellence.</p>
    </div>

    <div class="section">
        <h2>Experience</h2>

        <div class="job">
            <strong>Shooting Guard / Small Forward</strong> – Los Angeles Lakers (1996–2016)
            <ul>
                <li>Won 5 NBA Championships (2000, 2001, 2002, 2009, 2010), including three consecutive titles from 2000–2002</li>
                <li>Named NBA Finals MVP in 2009 and 2010</li>
                <li>Named NBA Most Valuable Player in 2008</li>
                <li>Scored 81 points vs. the Toronto Raptors on January 22, 2006 — the second-highest single-game total in NBA history</li>
                <li>Retired as the franchise all-time leading scorer with 33,643 career points (3rd in NBA history at time of retirement)</li>
                <li>Selected to 18 NBA All-Star Games; named All-Star Game MVP 4 times (2002, 2007, 2009, 2011)</li>
                <li>Named to 15 All-NBA teams and 12 NBA All-Defensive teams, including 9 First-Team All-Defensive selections</li>
                <li>Led the NBA in scoring in 2005–06 (35.4 PPG) and 2006–07 (31.6 PPG)</li>
                <li>Famously scored 60 points in his final NBA game (April 13, 2016) in a comeback win vs. the Utah Jazz</li>
            </ul>
        </div>

    </div>

    <div class="section">
        <h2>Education</h2>
        <div class="education">
            <strong>High School Diploma</strong> – Lower Merion High School, Ardmore, Pennsylvania (1996)
            <br>Named Pennsylvania Player of the Year; averaged 30.8 PPG, 12.0 RPG, 6.5 APG, and 4.0 BPG as a senior
        </div>
        <div class="education">
            <strong>Entered NBA Draft directly</strong> – Selected 13th Overall by Charlotte Hornets (traded to Lakers), 1996 NBA Draft
        </div>
    </div>

    <div class="section">
        <h2>Awards &amp; Honours</h2>
        <ul>
            <li>5× NBA Champion (2000, 2001, 2002, 2009, 2010)</li>
            <li>NBA Most Valuable Player (2008)</li>
            <li>2× NBA Finals MVP (2009, 2010)</li>
            <li>18× NBA All-Star; 4× All-Star Game MVP</li>
            <li>15× All-NBA Team selections (11× First Team)</li>
            <li>12× NBA All-Defensive Team (9× First Team)</li>
            <li>2× NBA Scoring Champion (2006, 2007)</li>
            <li>2× Olympic Gold Medalist (2008 Beijing, 2012 London)</li>
            <li>Naismith Memorial Basketball Hall of Fame Inductee (2020)</li>
            <li>NBA 75th Anniversary Team (2021)</li>
            <li>Jersey numbers #8 and #24 both retired by the Los Angeles Lakers</li>
        </ul>
    </div>

    <div class="section">
        <h2>Skills</h2>
        <p>Mid-Range Shooting, Post-Up Offense, Footwork &amp; Fadeaway, Perimeter Defense, Clutch Performance, Isolation Scoring, Free-Throw Shooting, Pick-and-Roll Defense, Leadership Under Pressure, Film Study &amp; Opponent Preparation, Mamba Mentality, Multilingual Communication (English, Italian, Spanish)</p>
    </div>

    <div class="section">
        <h2>Off-Court</h2>
        <ul>
            <li>Founder, Kobe Inc. — investment firm with early stakes in BodyArmor sports drink (sold to Coca-Cola)</li>
            <li>Founder, Granity Studios — multimedia content company focused on youth storytelling and sports</li>
            <li>Author of <em>The Mamba Mentality: How I Play</em> (2018)</li>
            <li>Academy Award winner — Best Animated Short Film for <em>Dear Basketball</em> (2018)</li>
            <li>Youth basketball coach — coached daughter Gianna's AAU team, Mamba Sports Academy</li>
        </ul>
    </div>

</body>
</html>