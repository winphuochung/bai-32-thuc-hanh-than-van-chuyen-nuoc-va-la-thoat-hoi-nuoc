# Web/app học tập — Khoa học tự nhiên 7, Bài 32

**Bài 32 — TH: Chứng minh thân vận chuyển nước và lá thoát hơi nước**
Môn Khoa học tự nhiên 7 — Chương VII: Trao đổi chất và chuyển hóa năng lượng ở sinh vật, sách Kết nối tri thức với cuộc sống (SGK tr. 136–137). Tuần 26, Tiết 102–103.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm — trò chơi “Thân và lá”), Vận dụng.

Bài thực hành với 2 thí nghiệm:

1. **Chứng minh thân vận chuyển nước** — Cắt ngang cuống cần tây (hoặc cành hoa trắng), cắm vào cốc nước pha màu, để chỗ thoáng. Sau 30–60 phút, cuống và lá bị nhuộm màu; cắt đoạn ngắn, soi kính lúp thấy mạch dẫn nhuộm màu → nước được vận chuyển từ rễ qua thân lên lá nhờ mạch gỗ.
2. **Chứng minh lá thoát hơi nước** — Chậu A ngắt toàn bộ lá (cây đối chứng), chậu B giữ nguyên lá; trùm túi nylon trong suốt, kín lên cả hai chậu, đặt ra ngoài sáng. Sau 15–30 phút, mặt trong túi ở chậu B xuất hiện các giọt nước, chậu A không có (hoặc rất ít) → lá thoát hơi nước ra môi trường.

Mô phỏng gồm 2 thí nghiệm với hình minh họa SVG nội tuyến thay đổi theo từng bước (chọn mực xanh/đỏ, kéo thanh thời gian, nút “Chạy thí nghiệm”).

Đáp án trắc nghiệm: ABABABAABA (1A 2B 3A 4B 5A 6B 7A 8A 9B 10A).

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp (danh sách chọn 12 lớp 6A1–9A3), học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm tự động lưu về Google Sheets của giáo viên (qua Apps Script Web App, chạy bằng tài khoản giáo viên).
- Tiến độ và điểm cao nhất được lưu theo từng học sinh trên thiết bị (localStorage).

## File trong thư mục

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64, đã gồm tính năng nộp điểm về Google Sheets).
- `Web_Hoc_Tap_KHTN7_Bai32.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — mã Apps Script Web App ghi điểm về Sheet (tab `KetQua`).
- `assets-flow/` — 3 ảnh nền JPG 1376×768 (hero, nền chính, nền đăng nhập) + logo cá nhân `logo-le-van-thang.png` (500×500, nền trong suốt).

## Ghi chú kỹ thuật

- Giao diện theo phong cách web/app KHTN 7 Bài 15: nền chính là ảnh phong cảnh ở body với lớp phủ nhẹ (ảnh hiện rõ sau thẻ trắng và sidebar), chế độ tối, thanh tiến độ, nút đổi cỡ chữ A−/A+, mục lục có vòng số, hero phủ veil + châm ngôn, trắc nghiệm dạng nút có nhãn Dễ/Trung bình/Khó, hộp thoại xác nhận đăng xuất/nộp bài, thanh điều hướng dưới đáy cho điện thoại.
- Ảnh nền tạo bằng Gemini / Google Flow, đều là phong cảnh, không có hình người.
- Nội dung đối chiếu với PDF bài giảng (SGK tr. 136–137): trình tự thí nghiệm, thời gian 30–60 phút / 15–30 phút, Bảng 32.1, 2 câu hỏi SGK và 10 câu trắc nghiệm đều khớp.
