# Telegram-Order-Notifier
A powerful WordPress plugin that connects your WooCommerce store to Telegram. Get instant order notifications with detailed stats, track completed, processing, and cancelled orders in real-time, and stay on top of your business—all from your Telegram app. Easy setup, sleek admin interface, and insightful store analytics included!
![Plugin Banner](https://www2.0zz0.com/2025/03/28/16/918821947.png)  
*Instant order updates, right where you need them.*

---

## Features

- **Real-Time Notifications**: Get instant alerts for completed, processing, and cancelled orders on Telegram.
- **Detailed Order Info**: View order number, customer details, shipping address, items, and total amount in every notification.
- **Customizable Alerts**: Choose which order statuses (completed, processing, cancelled) you want to track.
- **Store Analytics**: Access monthly sales, order stats, and product insights from the WordPress dashboard.
- **Easy Setup**: Simple 3-step configuration with automatic Chat ID detection.
- **Test Notifications**: Send a test message to ensure your Telegram integration works perfectly.
- **User-Friendly Interface**: Clean admin panel with a setup guide and video tutorial placeholder.

---

## Requirements

- WordPress 4.7 or higher
- WooCommerce 3.0 or higher
- PHP 5.6 or higher
- A Telegram account and bot (created via BotFather)

---

## Installation

1. **Download**: Clone this repository or download the ZIP file.
2. **Upload**: Upload the plugin folder to your WordPress site under `/wp-content/plugins/`.
3. **Activate**: Go to **Plugins** in your WordPress dashboard and activate "TeliWooCom".
4. **Configure**: Navigate to **Telegram Notifier > Settings** in the WordPress admin menu to set up your bot.

---

## Setup Guide

1. **Start the Bot**:
- Go to the plugin settings page in WordPress.
- Click "Start Telegram Bot" to open the bot link (`http://t.me/WoocommerceOrder_bot`).
2. **Authorize the Bot**:
- Send `/start` to the bot in Telegram.
- The plugin will automatically detect your Chat ID.
3. **Save Settings**:
- Select the order statuses you want notifications for (e.g., completed, processing, cancelled).
- Click "Save Settings" to finalize the setup.
4. **Test It**:
- Use the "Send Test Notification" button to confirm everything works.

---

## Usage

Once configured, TeliWooCom runs in the background. You'll receive Telegram messages like this for every tracked order:
📦 Order Number: #1234
👤 Customer Name: Ahmed Mohamed
📱 Tel: +20123456789
📍 Address:
123 Main St, Cairo, Egypt
🛍️ Order Details:
• 2 × T-Shirt (Black)
Unit Price: $10.00
Total: $20.00
💰 Total: $20.00
📊 Order Status: Completed

Check the **Statistics** page in WordPress for a breakdown of your store's performance, including total sales, average order value, and more.

---

## Screenshots

1. **Settings Page**  
   ![Settings Page](https://www2.0zz0.com/2025/03/28/19/268405528.png)

2. **Statistics Dashboard**  
   ![Stats Dashboard](https://www2.0zz0.com/2025/03/28/19/975066020.png)

3. **Telegram Notification**  
   ![Notification Example](https://www2.0zz0.com/2025/03/28/19/725982046.png)

---

## Contributing

We welcome contributions! To get started:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## Support

Got questions or need help?  
- Open an issue on this repository.  
- Contact the developer: [Facebook](https://fb.com/yassinelnoshokey).

---

## License

This project is licensed under the [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html) - see the [LICENSE](LICENSE) file for details.

---

## Credits

Developed by [Yassin Elnoshokey](https://fb.com/yassinelnoshokey).
