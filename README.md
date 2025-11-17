# CLOCK
A dockable FreeCAD time-management macro featuring Local/Global Clock, Stopwatch with XLSX logging, Countdown Timer, Daily Alarm, Pomodoro with sound, and a tamper-resistant Exam Mode that auto-cycles global time zones. Supports custom sounds, wide zone coverage, and optional Excel export.
A multifunctional macro that adds a full time-tracking panel to FreeCAD, including:
Local & Global Clock, Stopwatch with XLSX logging, Countdown Timer, Daily Alarm, Pomodoro Timer, and a tamper-resistant Exam Mode that auto-cycles global time zones. Ideal for engineering workflows, productivity tracking, and exam recording integrity.

✨ Features
🕰 Clock

Local time display

Global time display for multiple world zones

Quick switch between local & global views

⏱ Stopwatch

Start/stop/reset

Automatically logs time to Excel (XLSX)

Per-document project time records

Optional openpyxl support for enhanced export

⏳ Countdown Timer

HH:MM:SS duration

Pause/resume

Selectable alarm sound

Popup notification when finished

⏰ Daily Alarm

Fires at set time (local or selected time zone)

Weekday repeat rules (Mon–Sun)

Single-day (one-shot) alarm when no repeats selected

Time-remaining preview

🍅 Pomodoro Timer

Focus & Break durations

End-of-phase alarm sounds

Multiple sound play cycles

Automatic phase switching

📝 Exam Mode (Anti-Tamper)

Displays a global clock that auto-cycles time zones

Makes video/audio exam recordings extremely tamper-resistant

Adjustable cycle interval

Useful for verification and integrity of timed work

📦 Installation

Download the macro file (Clock_02.py) from this repository.

Place it in your FreeCAD Macro directory:

Windows: %APPDATA%\FreeCAD\Macro\

Linux: ~/.local/share/FreeCAD/Macro/

macOS: ~/Library/Preferences/FreeCAD/Macro/

Open FreeCAD → Macro → Execute Macro → select Clock_02.py.

A dockable panel named CLOCK will appear on the right side.

(Optional) Create a folder named Alarm_Sounds next to your macro for custom .wav alarms.

🗂 Data Logging (XLSX)

The macro automatically logs Stopwatch entries to:

Macro_Directory/Macro_03/Technical_Data/Project_Time_Data.xlsx


If the folder doesn’t exist, the macro will create it.

Enable openpyxl for best Excel compatibility.

🔧 Configuration

Alarm sounds: place .wav files in Alarm_Sounds/

Global Time Zones: editable in the GLOBAL_ZONES dictionary

Exam Mode cycle speed: adjustable in UI (default 5 seconds)

📸 Screenshots

![Clock View](images/clock.png)
![Stopwatch](images/stopwatch.png)
![Countdown](images/countdown.png)
![Pomodoro](images/pomodoro.png)
![Exam Mode](images/exam.png)

🧪 Compatibility

Tested on FreeCAD 1.1 (Dev)

Windows confirmed

Linux/macOS compatible except for Windows-specific sound methods (won’t break functionality)

🤝 Contributing

Contributions are welcome!

Report issues via GitHub Issues

Submit PRs for bug fixes or new features

Suggestions for additional time zones or exam-integrity tools are encouraged

📜 License

You may choose one:

MIT License (recommended for macros & tools)

🙏 Acknowledgments

This macro was built for users needing reliable time tracking, workflow logging, and exam-mode integrity inside FreeCAD. Thanks to the FreeCAD community for tools, testing, and feedback.
