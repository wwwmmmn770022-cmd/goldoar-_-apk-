# Goldora Flutter Starter

واجهة عميل عربية RTL لمتجر الذهب والمجوهرات.

## البيئة
- Flutter 3.47.x
- Dart 3.13+
- GetX
- Dio

## التشغيل
```bash
flutter pub get
flutter run --dart-define=API_BASE_URL=http://10.0.2.2:8000/api/v1 --dart-define=MEDIA_BASE_URL=http://10.0.2.2:8000 --dart-define=STORE_ID=1
```

> على Android Emulator استخدم `10.0.2.2` بدل `127.0.0.1` للوصول إلى Laravel على جهاز الكمبيوتر.

## ما تم تجهيزه
- Theme فاخر أسود/ذهبي/عاجي.
- RTL + العربية.
- API Client مع Dio.
- تخزين آمن للتوكن.
- Models للمنتج والقطعة والسعر.
- Repository + GetX Controller.
- صفحة رئيسية فعلية متصلة بـ `/products`.
- صفحة تفاصيل المنتج.
- حالات Loading / Empty / Error.
