# 🔐 PassManager – Password Manager (LocalStorage Version)

PassManager is a lightweight password management web application built using Next.js and browser LocalStorage.  
This version does not use a backend database and stores credentials directly in the user's browser.

It is ideal for learning client-side state management and CRUD operations without backend integration.<br><br>
![PM Architecture](public/Screenshot%202025-10-25%20184052.png)

---

## 🚀 Features

- Add website credentials (Site, Username, Password)
- Store data securely in browser LocalStorage
- View saved passwords dynamically
- Delete stored credentials
- Simple and responsive UI
- No backend required

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Next.js 14 | Frontend Framework |
| React      | UI & State Management |
| LocalStorage | Client-side data storage |
| CSS / Tailwind | Styling |

---

## 📂 Project Structure

```
PassManager-LocalStorage/
│
├── app/
│   └── page.js             # Main application UI
│
├── components/             # Reusable UI components
├── public/                 # Static assets
└── package.json
```

---

## ⚙️ How It Works

1. User enters website name, username, and password.
2. Data is saved in browser LocalStorage using JavaScript.
3. Stored credentials are fetched and displayed dynamically.
4. Users can delete saved entries.
5. Data persists in the browser until manually cleared.

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/PassManager-LocalStorage.git
cd PassManager-LocalStorage
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Development Server

```bash
npm run dev
```

Open in browser:

```
http://localhost:3000
```

---

## ⚠️ Limitations

- Data is stored only in the browser.
- Clearing browser cache will delete all saved passwords.
- No encryption implemented.
- No user authentication.

---

## 📈 Future Improvements

- Add password encryption
- Implement authentication system
- Sync data with backend database
- Add edit functionality
- Password strength checker
- Dark mode support

---

## 👨‍💻 Author

Developed as a frontend-based password manager project using Next.js and LocalStorage.

---

## 📜 License

This project is licensed under the MIT License.
