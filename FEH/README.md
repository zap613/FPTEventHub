# 🎉 FPTEventHub (Vite + React)

**FPTEventHub** là hệ thống quản lý sự kiện sinh viên được phát triển dành riêng cho sinh viên, giảng viên và quản trị viên tại Đại học FPT. Hệ thống cho phép người dùng đăng nhập, xem và quản lý các sự kiện học thuật, nghề nghiệp và giải trí một cách hiệu quả.

---

## 🚀 Tính năng chính

### 🧑‍💻 Người dùng
- Đăng ký / Đăng nhập bằng email `@fpt.edu.vn`
- Xem danh sách sự kiện theo phân trang (9 sự kiện/trang)
- Truy cập chi tiết từng sự kiện
- Carousel hiển thị 3 sự kiện nổi bật (tự động chuyển)

### 📋 Admin
- Quản lý người dùng (sinh viên, giảng viên)
- Tạo, chỉnh sửa, xóa sự kiện
- Import danh sách sự kiện từ file
- Xem thống kê sự kiện theo số lượng đăng ký

### 👨‍🏫 Giảng viên
- Tạo các sự kiện liên quan đến học thuật
- Xem danh sách sinh viên tham gia

---

## 📁 Cấu trúc thư mục
src/
├── assets/              # Hình ảnh logo, sự kiện, campus
│   ├── FPTCampus.png
│   ├── FPTLogo.png
│   └── events/
├── components/          # Các component React chính
│   ├── HomePage.jsx
│   ├── Login.jsx
│   ├── Register.jsx
│   └── ForgotPassword.jsx
├── styles/              # CSS Modules
│   ├── AuthForm.module.css
│   └── HomePage.module.css
├── utils/               # Hàm tiện ích và dữ liệu mẫu
│   ├── authUtils.js
│   └── mockEvents.js
├── App.jsx              # Khai báo router và layout chính
├── main.jsx             # Điểm khởi chạy với ReactDOM
└── index.css            # CSS toàn cục

## 📦 Công nghệ sử dụng
    Loại	    Công cụ
🧠 Frontend	    ReactJS, Vite
🔀 Router	    React Router DOM
💅 UI	        Material UI (MUI)
🎨 CSS	        CSS Modules
🔒 Auth	        LocalStorage, SessionStorage
📦 Mock Data	mockEvents.js, authUtils.js

## ⚙️ Khởi động dự án

```bash
# Cài đặt các dependencies
npm install

# Chạy ứng dụng ở môi trường phát triển
npm run dev
