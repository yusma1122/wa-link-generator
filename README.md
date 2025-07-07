# 📱 WhatsApp Link Generator Pro

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-2.0-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

> **Generate WhatsApp links easily, quickly, and elegantly!**

A simple yet powerful web application for creating WhatsApp links with pre-formatted messages. Complete with QR Code generator, message templates, and modern interface.

## ✨ Key Features

### 🎯 **Core Features**
- **WhatsApp Link Generator** - Create wa.me links with automatic number and message formatting
- **QR Code Generator** - Generate QR codes for WhatsApp links
- **Message Templates** - 4 ready-to-use templates (Business, Personal, Service, Product)
- **Auto Number Formatting** - Automatic Indonesian number formatting (0xxx → 62xxx)
- **Input Validation** - Phone number and message validation

### 🚀 **Advanced Features**
- **Share Integration** - Native Web Share API with fallback
- **Download QR Code** - Download QR code as PNG
- **Copy to Clipboard** - Copy link with one click
- **Character Counter** - Count message characters (max 500)
- **Responsive Design** - Mobile-first and desktop friendly

### 🎨 **UI/UX Features**
- **Modern Design** - Glassmorphism effect with gradients
- **Smooth Animations** - Smooth transitions and micro-interactions
- **Notification System** - Toast notifications for user feedback
- **Dark Mode Ready** - Ready for dark mode implementation

## 🖥️ Demo

![WhatsApp Link Generator Demo](https://yusma1122.github.io/wa-link-generator/)

**[🔗 Live Demo](https://your-demo-link.com)** | **[📱 Mobile Preview](https://your-mobile-demo.com)**

## 🚀 Quick Start

### 1. **Clone Repository**
```bash
git clone https://github.com/yusma-rahman/wa-link-generator-pro.git
cd wa-link-generator-pro
```

### 2. **Local Setup**
```bash
# No dependencies installation required
# Simply open HTML file in browser

# Or use Live Server (VS Code Extension)
# Or Python Simple Server
python -m http.server 8000
```

### 3. **Access Application**
```
http://localhost:8000
```

## 📁 File Structure

```
wa-link-generator-pro/
├── index.html              # Main application file
├── README.md               # This documentation
├── LICENSE                 # MIT License
```

## 🎯 How to Use

### **Step 1: Enter Phone Number**
- Input target WhatsApp number
- Format: `08123456789` or `628123456789`
- System will automatically format to international format

### **Step 2: Write Message**
- Type the message you want to send
- Or select from available templates
- Maximum 500 characters

### **Step 3: Generate Link**
- Click "🚀 Generate Link" button
- WhatsApp link and QR Code will appear
- Use various available options

### **Additional Options**
- **💬 Open WhatsApp** - Open directly in WhatsApp
- **📋 Copy Link** - Copy link to clipboard
- **📤 Share** - Share link (if browser supports)
- **💾 Download QR** - Download QR code
- **🔄 Generate New** - Create new link without resetting form

## 🛠️ Technologies

| Technology | Function | Version |
|-----------|----------|---------|
| **HTML5** | Application structure | - |
| **CSS3** | Styling and animations | - |
| **JavaScript (ES6+)** | Application logic | - |
| **Tailwind CSS** | CSS Framework | 3.x |
| **QR Server API** | QR Code generation | - |
| **Web APIs** | Clipboard, Share, Storage | - |

### **Change Theme Colors**
```css
/* Change gradient background */
.gradient-bg {
    background: linear-gradient(135deg, #your-color-1, #your-color-2);
}

/* Change primary button color */
.btn-primary {
    background: linear-gradient(to right, #your-color-1, #your-color-2);
}
```

### **Add Other Country Validation**
```javascript
function isValidPhoneNumber(nomor) {
    // Add validation for other countries
    const patterns = {
        indonesia: /^62\d{9,13}$/,
        malaysia: /^60\d{9,10}$/,
        singapore: /^65\d{8}$/
    };
    
    return patterns.indonesia.test(nomor); // Adjust as needed
}
```

## 📊 Browser Support

| Browser | Support | Version |
|---------|---------|---------|
| Chrome | ✅ | 60+ |
| Firefox | ✅ | 55+ |
| Safari | ✅ | 12+ |
| Edge | ✅ | 79+ |
| Opera | ✅ | 47+ |
| Mobile Safari | ✅ | 12+ |
| Chrome Mobile | ✅ | 60+ |

## 🔒 Security & Privacy

- **No Data Storage** - No data stored on server
- **Client-Side Only** - All processing in browser
- **No Cookies** - No cookies used
- **HTTPS Ready** - Ready for HTTPS deployment
- **XSS Protection** - Input sanitization implemented

## 📈 Performance

- **Lightweight** - Single HTML file < 50KB
- **Fast Loading** - Minimal dependencies
- **SEO Friendly** - Semantic HTML structure
- **Mobile Optimized** - Mobile-first approach
- **Accessible** - ARIA labels and keyboard navigation

## 🤝 Contributing

Contributions are very welcome! Please read [CONTRIBUTING.md](docs/CONTRIBUTING.md) for detailed guidelines.

### **How to Contribute**
1. Fork this repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Create Pull Request

### **Contributors**
- [Yusma Rahman](https://github.com/yusma1122) - Creator & Maintainer

## 📝 Changelog

### **v2.0** (2025-01-xx)
- ✨ UI redesign with glassmorphism
- ✨ Automatic message templates
- ✨ Share integration
- ✨ Download QR code
- ✨ Notification system
- 🐛 Fix number validation
- 🎨 Improve mobile responsiveness

### **v1.0** (2024-xx-xx)
- 🎉 Initial release
- 📱 Basic WhatsApp link generator
- 🔗 QR code generation
- 📋 Copy to clipboard

## 📞 Contact & Support

- **Developer**: Yusma Rahman
- **LinkedIn**: [linkedin.com/in/yusmarahman09](https://www.linkedin.com/in/yusmarahman09/)
- **Instagram**: [@yusmafrlnc](https://instagram.com/yusmafrlnc)

## 📄 License

This project is licensed under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2025 Yusma Rahman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com) - For amazing utility-first CSS framework
- [QR Server](https://qrserver.com) - For free QR code generation API
- [Heroicons](https://heroicons.com) - For beautiful SVG icons
- [Unsplash](https://unsplash.com) - For free high-quality images

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [Yusma Rahman](https://github.com/yusma1122)

</div>