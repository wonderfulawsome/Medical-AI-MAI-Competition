# 데이터셋 정보

## Train 폴더
- 학습용 H&E 염색된 조직 이미지 샘플 6,992개가 포함되어 있음.
- **파일 이름**: `TRAIN_0000.png` ~ `TRAIN_6991.png`

## Test 폴더
- 평가용 H&E 염색된 조직 이미지 샘플 2,277개가 포함되어 있음.
- **파일 이름**: `TEST_0000.png` ~ `TEST_2276.png`

## train.csv
- **컬럼**:
  - `ID`: 샘플 ID
  - `path`: H&E 염색된 조직 이미지 경로
  - `AL645608.7` ~ `AL592183.1`: 각 유전자의 발현 정보 (총 3,467개 유전자)

## test.csv
- **컬럼**:
  - `ID`: 샘플 ID
  - `path`: H&E 염색된 조직 이미지 경로

## sample_submission.csv
- **컬럼**:
  - `ID`: 샘플 ID
  - `AL645608.7` ~ `AL592183.1`: 예측한 각 유전자의 발현 정보 (총 3,467개 유전자)

![이미지 설명](https://postfiles.pstatic.net/MjAyNDEwMDRfMTc0/MDAxNzI4MDIwNDYwMjM5.gpe2l86Rq9rlwZbhA8pOc0buNgquh7Aw6OsCpGqxUEMg.3k2eTQSMzwEK33lX9FljB65v9OV2XrqnYYghofWu1dcg.PNG/236382-MAI-poster-%EC%B5%9C%EC%A2%85%EB%B3%B8.png?type=w3840)
