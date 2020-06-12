https://kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9791161751825&orderClick=JAj

# Mastering Spring 5.0
This is the code repository for [Mastering Spring 5.0](https://www.packtpub.com/application-development/mastering-spring-50?utm_source=github&utm_medium=repository&utm_campaign=9781787123175), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Spring 5.0 is due to arrive with a myriad of new and exciting features that will change the way we’ve used the framework so far. This book will show you this evolution—from solving the problems of testable applications to building distributed applications on the cloud.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

Chapters 1, 4, and 12 does not have code files.

The code will look like the following:
```
<properties>
    <mockito.version>1.10.20</mockito.version>
</properties>
```

To be able to run examples from this book, you will need the following tools:

Java 8
Eclipse IDE
Postman

We will use Maven embedded into Eclipse IDE to download all the dependencies that are needed.

## Related Products
* [Learning Spring 5.0](https://www.packtpub.com/application-development/learning-spring-50?utm_source=github&utm_medium=repository&utm_campaign=9781787120341)

* [Essentials of Spring 5.0 for Developers [Video]](https://www.packtpub.com/application-development/essentials-spring-50-developers-video?utm_source=github&utm_medium=repository&utm_campaign=9781787283893)

* [Spring 5.0 Recipes](https://www.packtpub.com/application-development/spring-50-recipes?utm_source=github&utm_medium=repository&utm_campaign=9781787128316)


1장. 스프링 프레임워크 5.0의 발전
 - 스프링 프레임워크
 -   EJB 관련 문제점
 - 스프링 프레임워크가 인기 있는 이유는 무엇일까?
 -   단순화된 단위 테스트
 -   복잡한 코드 감소
 --      스프링 프레임워크는 어떻게 마법을 부릴까?
 -   아키텍처의 유연성
 -   변화하는 시대를 선도함
 - 스프링 모듈
 -   스프링 코어 컨테이너
 -   횡단 관심
 -   웹
 -   비지니스
 -   데이터
 - 스프링 프로젝트
 -   스프링 부트
 -   스프링 클라우드
 -   스프링 데이터
 -   스프링 배치
 -   스프링 시큐리티
 -   스프링 HATEOAS
 - 스프링 프레임워크 5.0 새로운 기능
 -   기준선 업그레이드
 -   JDK 9 런타임 호환성
 -   스프링 프레임워크 코드에서 JDK 8 기능 사용
 -   리액티브 프로그래밍 지원
 -   함수형 웹 프레임워크
 -   직소를 사용한 자바 모듈성
 -   코틀린 지원
 -   삭제된 기능
 - 스프링 부트 2.0의 새로운 기능
 - 요약

2장. 의존성 주입
 - DI 이해하기
 -   의존성 이해하기
 -   스프링 IoC 컨테이너
 --      빈과 와이어링 정의
 --      스프링 IoC 컨테이너 생성
 --      애플리케이션 콘텍스트에 대한 자바 구성
 --      애플리케이션 콘텍스트의 XML 구성
 --      스프링 콘텍스트를 사용해 JUnit 작성하기
 -   모크 단위 테스트
 -   컨테이너 관리 빈
 -   DI 유형
 --      setter 주입
 --      생성자 주입
 --      생성자 대 설정자 주입
 -   스프링 빈 스코프
 -   자바 대 XML 구성
 -   @Autowired 어노테이션
 --      @Primary 어노테이션
 --      @Qualifier 어노테이션
 -   기타 중요한 스프링 어노테이션
 -   콘텍스트 및 DI 탐색
 --      CDI의 예
 - 요약

3장. 스프링 MVC 웹 애플리케이션 구축
 - 자바 웹 애플리케이션 아키텍처
 -   모델 1 아키텍처
 -   모델 2 아키텍처
 -   모델 2 프런트 컨트롤러 아키텍처
 - 기본 플로
 -   기존 설정
 --      스프링 MVC에 대한 의존성 추가하기
 --      DispatcherServlet을 web.xml에 추가하기
 --      스프링 콘텍스트 생성하기
 -   플로 1 - 뷰 없는 간단한 컨트롤러 플로
 --      스프링 MVC 컨트롤러 생성하기
 --      웹 애플리케이션 구동
 --      단위 테스트
 -   플로 2 - 뷰를 가진 간단한 컨트롤러 플로
 --      스프링 MVC 컨트롤러
 --      뷰 생성하기 - JSP
 --      단위 테스트
 -   플로 3 - 모델이 있는 뷰로 전환하는 컨트롤러
 --      스프링 MVC 컨트롤러
 --      뷰 생성하기
 --      단위 테스팅
 -   플로 4 - ModelAndView를 사용해 뷰로 전환하는 컨트롤러
 --      스프링 MVC 컨트롤러
 --      뷰 생성하기
 --      단위 테스팅
 -   플로 5 - 폼이 있는 뷰로 전환하는 컨트롤러
 --      명령 또는 폼 백엔드 오브젝트 작성하기
 --      폼을 표시하는 컨트롤러 메서드
 --      폼을 가진 뷰 생성하기
 -     컨트롤러가 폼 제출을 처리하는 메서드를 가져오기
 --      단위 테스팅
 -   플로 6 - 이전 플로에 유효성 검증 추가하기
 --      하이버네이트 벨리데이터 의존성
 --      빈에 대한 간단한 검증
 --      커스텀 벨리데이션
 --      유닛 테스팅
 - 스프링 MVC의 개요
 -   중요 기능
 -   어떻게 작동할까?
 - 스프링 MVC의 핵심 개념
 -   RequestMapping
 --      요청 매핑 예제
 --      요청 매핑 메서드 - 지원되는 메서드 인수
 --      RequestMapping 메서드 - 지원되는 리턴 유형
 -   뷰 리솔루션
 --      JSP 뷰 리졸버 구성하기
 --      프리마커 구성
 -   핸들러 매핑과 인터셉터
 --      HandlerInterceptor 정의하기
 --      HandlerInterceptor를 핸들러에 매핑
 -   모델 속성
 -   세션 속성
 --      세션에 속성 추가하기
 --      세션에서 속성 읽기
 --      세션에서 속성 제거
 -   InitBinders
 -   @ControllerAdvice 어노테이션
 - 스프링 MVC - 고급 기능
 -   예외 처리
 --      컨트롤러 전반의 일반적인 예외 처리
 --      컨트롤러의 특정 예외 처리
 -   국제화
 --      메시지 번들 설정
 --      SessionLocaleResolver 설정
 --      CookieLocaleResolver 설정
 -   스프링 컨트롤러 통합 테스트
 -   정적 자원 제공
 --      정적 콘텐츠 노출
 --      정적 콘텐츠 캐싱
 --      정적 콘텐츠의 GZip 압축 사용
 -   스프링 MVC와 부트스트랩의 통합
 --      메이븐 의존성으로서의 부트스트랩 WebJar
 --      스프링 MVC 리소스 핸들러로 WebJar 정적 콘텐츠 전달하기 설정
 --      JSP에서 부트스트랩 리소스 사용하기
 - 스프링 시큐리티
 -   스프링 보안 의존성 추가하기
 -   모든 요청을 인터셉트하도록 필터 설정
 -   로그아웃


4장. 마이크로 아키텍처 및 클라우드-네이티브 애플리케이션으로의 진화
 - 스프링을 이용한 일반적인 웹 애플리케이션 아키텍처
 -   웹 계층
 --      웹 애플리케이션 - HTML 뷰 렌더링
 --      RESTful 서비스
 -   비즈니스 계층
 -   데이터 계층
 -   통합 계층
 -   횡단 관심
 - 스프링에 의해 해결된 문제
 -   느슨한 커플링 및 테스트 가능성
 -   복잡한 코드
 -   경량 아키텍처
 -   유연한 아키텍처
 -   횡단 관심의 간편한 구현
 -   디자인 패턴
 - 애플리케이션 개발 목표
 -   속도
 -   안전
 --      신뢰성
 --      가용성
 --      보안
 --      성능
 --      높은 복원력
 -   확정성
 - 모놀리식 애플리케이션 문제
 -   긴 릴리스 주기
 -   확장의 어려움
 -   새로운 기술 적용
 -   새로운 방법론 적용
 -   현대적인 개발 사례 적용
 - 마이크로서비스 이해
 -   마이크로서비스는 무엇인가?
 -   마이크로서비스 아키텍처
 -   마이크로서비스 특성
 --      작고 가벼운 마이크로서비스
 --      메시지 기반 커뮤니케이션과의 상호 운용성
 --      용량 할당 마이크로서비스
 --      독립적으로 배포 가능한 유닛
 --      무상태
 --      자동화된 빌드 및 릴리스 프로세스
 --      이벤트-드리븐 아키텍처
 --      독립된 팀
 -   마이크로서비스 장점
 --      출시 시간 단축
 --      기술 진화
 --      가용성 및 확장성
 --      팀 동력
 -   마이크로서비스 문제
 --      자동화에 대한 필요성 증가
 --      서브 시스템의 경계 정의
 --      가시성 및 모니터링
 --      결함 허용
 --      영속적 일관성
 --      운영 팀에 대한 필요성 증가
 - 클라우드-네이티브 애플리케이션
 -   12-팩터 앱
 --      코드베이스 유지
 --      의존성
 --      환경 설정
 --      백엔드 서비스
 --      빌드, 릴리스, 실행
 --      무상태
 --      포트 바인딩
 --      동시성
 --      처분 가능성
 --      환경 평가
 --      이벤트 스트림 로그
 --      구분 없는 어드민 프로세스
 - 스프링 프로젝트
 -   스프링 부트
 -   스프링 클라우드
 - 요약

5장. 스프링 부트로 마이크로서비스 구축
 - 스프링 부트는 무엇인가?
 -   마이크로서비스로 빠르게 프로토타입 구축
 -   기본 목표
 -   비기능적인 특징
 - 스프링 부트 Hello World
 -   spring-boot-starter-parent 설정
 --      spring-boot-starter-parent
 -   필요한 스타터 프로젝트를 사용해 pom.xml 구성
 --      스타터 프로젝트 이해하기
 -   spring-boot-maven-plugin 설정
 -   첫 스프링 부트 구동 클래스 생성
 --      SpringApplication 클래스
 --      @SpringBootApplication 어노테이션
 -   Hello World 애플리케이션 구동
 -   자동 설정
 -   스타터 프로젝트
 - REST는 무엇인가?
 - 첫 REST 서비스
 -   문자열을 반환하는 간단한 메서드
 --      단위 테스팅
 --      통합 테스팅
 -   객체를 반환하는 간단한 REST 메서드
 --      요청 실행
 --      단위 테스팅
 --      통합 테스팅
 -   경로 변수를 가진 Get 메서드
 --      요청 실행
 --      단위 테스팅
 --      통합 테스팅
 - todo 리소스 생성
 -   메서드, 오퍼레이션, URI 요청
 -   빈들과 서비스들
 -   Todo 리스트 검색
 --      서비스 실행
 --      단위 테스팅
 --      통합 테스팅
 -   특정 Todo의 세부 정보 검색
 --      서비스 실행
 --      단위 테스팅
 --      통합 테스팅
 -   Todo 추가
 --      포스트맨
 --      POST 서비스 실행
 --      단위 테스팅
 --      통합 테스트
 - 스프링 이니셜라이저
 -   첫 스프링 이니셜라이저 프로젝트 생성
 --      Pom
 --      FirstSpringInitializrApplication.java 클래스
 --      FirstSpringInitializrApplicationTests 클래스
 - 자동 설정 확인
 - 요약

6장. 마이크로서비스 확장
 - 예외 처리
 -   스프링 부트 기본 예외 처리
 --      존재하지 않는 리소스
 --      예외를 발생시키는 리소스
 --      커스텀 예외 발생시키기
 --      커스텀 예외 메시지
 --      응답 상태
 - HATEOAS
 -   응답에 HATEOAS 링크 정보 보내기
 --      스프링 부트 스타터 HATEOAS
 - 벨리데이션
 -   컨트롤러 메서드 벨리데이션 활성화
 -   빈 벨리데이션 정의
 -   단위 테스팅 벨리데이션
 - REST 서비스 문서화
 -   Swagger 명세서 생성
 --      Swagger UI
 --      어노테이션을 사용한 커스텀 Swagger 문서
 - 스프링 시큐리티로 REST 서비스 보호
 -   스프링 시큐리티 스타터 추가
 -   기본 인증
 --      통합 테스팅
 --      단위 테스팅
 -   OAuth 2 인증
 --      하이-레벨 플로
 --      서비스를 OAuth 2로 인증 구현
 - 국제화
 - 캐싱
 -   Spring-boot-starter-cache
 -   캐싱 활성화
 -   데이터 캐싱
 -   JSR-107 캐싱 어노테이션
 --      자동 감지 순서
 - 요약

7장. 고급 스프링 부트 기능
 - 외형화된 구성
 -   application.properties를 통한 프레임워크 커스텀
 --      로깅
 --      임베디드 서버 구성
 --      스프링 MVC
 --      스프링 스타터 시큐리티
 --      데이터 소스, JDBC와 JPA
 --      기타 구성 옵션
 -   application.properties의 커스텀 속성
 --      구성 등록 정보 - 타입세이프(type-safe) 구성 관리
 -   프로파일
 --      프로파일-기반 빈 구성
 -   애플리케이션 구성값에 대한 기타 옵션
 -   YAML 구성
 - 임베디드 서버
 -   제티 및 언더토우 전환
 -   WAR 파일 만들기
 - 개발자 도구
 -   실시간 리로드
 - 스프링 부트 엑추에이터
 -   HAL 브라우저
 -   구성 속성
 -   환경 세부 정보
 -   상태
 -   매핑
 -   빈즈
 -   측정 항목
 -   자동 구성
 -   디버깅
 - 클라우드에 애플리케이션 배포
 -   클라우드 파운드리
 - 요약

8장. 스프링 데이터
 - 백그라운드 - 데이터 저장소
 - 스프링 데이터
 -   스프링 데이터 커먼즈
 --      리포지토리
 --      CrudRepository 인터페이스
 --      PagingAndSortingRepository 인터페이스
 -   스프링 데이터 JPA
 --      스프링 데이터 JPA 예제
 --      엔티티
 --      간단한 저장소
 --      CrudRepository 인터페이스
 --      PagingAndSortingRepository 인터페이스
 --      쿼리 메서드
 --      쿼리들
 - 스프링 데이터 Rest
 -   GET 메서드
 -   POST 메서드
 -   검색 리소스
 - 빅데이터
 -   몽고DB
 --      단위 테스트
 - 요약

9장. 스프링 클라우드
 - 스프링 클라우드 소개
 -   스프링 클라우드 넷플릭스
 - 데모 마이크로서비스 설정
 -   마이크로서비스 A
 -   서비스 소비자
 --      포트
 - 중앙 집중식 마이크로서비스 구성
 -   문제 기술
 -   해결책
 -   옵션
 -   스프링 클라우드 컨피그
 --      스프링 클라우드 컨피그 서버 구현
 - 스프링 클라우드 버스
 -   스프링 클라우드 버스의 필요성
 -   스프링 클라우드 버스를 사용해 구성 변경 전파
 -   구현
 - 선언적 REST 클라이언트 - 페인
 - 로드 균형 조정
 -   립본
 --      구현
 - 네임 서버
 -   마이크로서비스 URL 하드 코딩의 한계
 - 네임 서버 작동
 -   옵션
 -   구현
 --      유레카 서버 세팅
 --      유레카에 마이크로서비스 등록
 --      유레카와 서비스 소비자 마이크로서비스 연결
 - API 게이트웨이
 -   주울로 클라이언트 측 로드 밸런싱 구현하기
 --      새로운 주울 API 게이트웨이 서버 설정
 --      주울 API 게이트웨이를 사용하도록 서비스 소비자 구성
 - 분산 추적
 -   분산 추적 옵션
 -   스프링 클라우드 슬루스와 집킨 구현하기
 --      스프링 클라우드 슬루스와 마이크로서비스 컴포넌트 통합
 --      집킨 분산 추적 서버 설정
 --      집킨과 마이크로서비스 구성 요소 통합
 - 히스트릭스 - 내결함성
 -   구현
 - 요약

10장. 스프링 클라우드 데이터 플로
 - 메시지 기반 비동기 통신
 -   비동기 통신의 복잡성
 - 비동기 메시지용 스프링 프로젝트
 -   스프링 통합
 -   스프링 클라우드 스트림
 -   스프링 클라우드 데이터 플로
 - 스프링 클라우드 스트림
 -   스프링 클라우드 스트림 아키텍처
 -   이벤트 처리 - 주식 거래 예제
 --      주식 거래 예제 위한 모델
 --      소스 애플리케이션
 --      프로세서
 --      싱크
 - 스프링 클라우드 데이터 플로
 -   높은 수준의 아키텍처
 -   스프링 클라우드 데이터 플로 구현하기
 --      스프링 클라우드 데이터 플로 서버 설정하기
 --      데이터 플로 셸 프로젝트 설정
 --      앱 구성
 --      스트림 구성
 --      스트림 배포
 --      로그 메시지 - 메시지 팩토리에 대한 연결 설정
 --      로그 메시지 - 이벤트 플로
 -   스프링 클라우드 데이터 플로 REST API
 - 스프링 클라우드 테스크
 - 요약

11장. 리액티브 프로그래밍
 -   리액티브 선언
 -   리액티브 시스템의 특성
 - 반응적 사용 사례 - 주가 페이지
 -   전통적인 방식
 -   리액티브 방식
 -   전통적인 방식과 리액티브 방식의 비교
 - 자바의 리액티브 프로그래밍
 -   리액티브 스트림
 -   리액터
 --      모노
 --      플럭스
 -   스프링 웹 리액티브
 --      스프링 이니셜라이저를 사용해 프로젝트 만들기
 --      리액티브 컨트롤러 만들기
 --      HTML 보기 만들기
 --      SpringReactiveExampleApplication 실행
 -   리액티브 데이터베이스
 --      스프링 부트 리액티브 몽고DB 스타터 통합하기
 --      모델 오브젝트 생성 - Stock 도큐멘트
 --      ReactiveCrudRepository 만들기
 --      명령-행 러너를 사용해 주식 데이터 초기화하기
 --      레스트 컨트롤러에서 리액티브 함수 만들기
 --      이벤트 스트림에 가입하기 위해 뷰 업데이트하기
 --      SpringReactiveExampleApplication 실행 중
 - 요약

12장. 스프링 모범 사례
 - 메이븐 표준 디렉터리 레이아웃
 - 계층화된 아키텍처
 -   권장 사례
 --      중요한 레이어에 대한 API와 impl 분리
 - 예외 처리
 -   예외 처리에 대한 스프링의 접근 방식
 -   권장 접근법
 - 스프링 구성 간결하게 유지
 -   컴포넌트 스캔에서 basePackageClasses 특성 사용
 -   스키마 참조에서 버전 번호를 사용하지 않음
 -   필수 의존성에 대한 setter 인젝션보다 생성자 인젝션을 선호한다
 - 스프링 프로젝트의 의존성 버전 관리하기
 - 단위 테스트
 -   비즈니스 레이어
 -   웹 레이어
 -   데이터 레이어
 -   기타 모범 사례
 - 통합 테스트
 -   스프링 세션
 -   예제
 --      스프링 세션에 대한 의존성 추가하기
 --      HttpSession을 스프링 세션으로 대체하기 위한 필터 설정하기
 --      AbstractHttpSessionApplicationInitializer를 확장해 톰캣에 대한 필터링 사용
 - 캐싱
 -   스프링 부트 스타터 캐시 의존성 추가하기
 -   캐싱 어노테이션 추가하기
 - 로깅
 -   로그백
 -   Log4j2
 -   프레임워크 독립 구성
 - 요약

13장. 스프링에서 코틀린 개발
 - 코틀린
 - 코틀린 대 자바
 -   변수 및 형식 추론
 -   변수 및 불변성
 -   타입 시스템
 -   함수들
 -   배열
 -   컬렉션
 -   확인되지 않은 예외 처리
 -   데이터 클래스
 - 이클립스에서 코틀린 프로젝트 만들기
 -   코틀린 플러그인
 -   코틀린 프로젝트 만들기
 -   코틀린 클래스 만들기
 -   코틀린 클래스 실행
 - 코틀린을 사용해 스프링 부트 프로젝트 만들기
 -   의존성 및 플러그인
 -   스프링 부트 애플리케이션 클래스
 -   스프링 부트 애플리케이션 테스트 클래스
 - 코틀린을 사용해 REST 서비스 구현하기
 -   문자열을 리턴하는 간단한 메서드
 --      단위 테스트
 --      통합 테스트
 -   객체를 반환하는 간단한 REST 메서드
 --      요청 실행
 --      단위 테스트
 --      통합 테스트
 -   경로 변수로 메서드 가져오기
 --      요청 실행
 --      단위 테스트
 --      통합 테스트
