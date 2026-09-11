# YouTube Audio Bot 🎧

یه ربات تلگرامی که لینک یوتیوب می‌گیره و فقط صدای ویدیو رو برمی‌گردونه، مثل پادکست.
@MyYoutubeAudioDownloader_bot
## نصب

1. کلون کردن پروژه:
   git clone https://github.com/USERNAME/youtube-audio-bot.git

2. ساخت محیط مجازی:
   python3 -m venv venv
   source venv/bin/activate

3. نصب کتابخونه‌ها:
   pip install -r requirements.txt

4. نصب ffmpeg (لازمه برای تبدیل صدا)

5. ساخت فایل `.env` و اضافه کردن توکن:
   BOT_TOKEN=your_token_here

6. اجرا:
   python bot.py

## قابلیت‌ها
- گرفتن لینک یوتیوب
- دانلود و استخراج صدا (mp3)
- ارسال فایل صوتی به کاربر تو تلگرام



