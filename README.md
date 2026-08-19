# Podcast Player

**🎧 A Spotify-style audio player in a single HTML file — vanilla JavaScript, no dependencies, no build step.**

<div dir="rtl">

נגן אודיו בדף אינטרנט יחיד, בהשראת העיצוב של ספוטיפיי: תמונת קאבר עם רקע מטושטש, פס התקדמות גריר, וכפתורי ניגון. הנגן בנוי כקובץ `index.html` אחד עם JavaScript ו־CSS ונילה בלבד — בלי ספריות ובלי תהליך בנייה.

הגרסה במאגר מנגנת קליפ מוטמע: קטע רדיו של חן ליברמן וישי שנרב מ**כאן ב׳** (23 באפריל 2026, כ־12 דקות).

🔗 **הנגן החי:** [yairixstudio.github.io/podcast-player](https://yairixstudio.github.io/podcast-player/)

## פיצ'רים

- ▶️ ניגון / השהיה
- ⏪⏩ דילוג של 15 שניות אחורה וקדימה
- 🎯 פס התקדמות עם קליק וגרירה — עכבר ומגע (מובייל)
- ⌨️ קיצורי מקלדת: רווח לניגון/השהיה, חצים לדילוג של 15 שניות
- ⏱️ תצוגת זמן נוכחי וזמן כולל
- 🖼️ רקע מטושטש שנוצר מתמונת הקאבר
- 📱 עיצוב רספונסיבי, ממשק בעברית (RTL)

## הרצה מקומית

</div>

```bash
git clone https://github.com/yairixStudio/podcast-player.git
cd podcast-player

# Option 1: just open it
open index.html

# Option 2: serve it locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

<div dir="rtl">

## החלפת התוכן

הקליפ, התמונה והכיתובים מוטמעים ישירות בקוד. כדי לנגן משהו אחר:

1. החליפו את `audio.mp3` בקובץ האודיו שלכם
2. החליפו את `photo_130.jpg` בתמונת הקאבר שלכם
3. ערכו את הכותרת ואת כותרת המשנה ב־`index.html` (המחלקות `.title` ו־`.subtitle`)

## טכנולוגיות

- קובץ `index.html` יחיד — HTML, CSS ו־JavaScript ונילה, ללא תלויות
- נגן מבוסס `<audio>` של HTML5
- גופן [Heebo](https://fonts.google.com/specimen/Heebo) מ־Google Fonts
- פריסה אוטומטית עם **GitHub Pages** מענף `main`

## יוצר

**[Yairix Studio](https://yairix.com)**

- אתר: [https://yairix.com](https://yairix.com)
- מייל: yairixstudio@gmail.com

</div>
