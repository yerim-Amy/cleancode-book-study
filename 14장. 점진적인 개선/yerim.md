# 14장  점진적인 개선

Args는 사용법이 간단하다. Args 생성자에 (입력으로 들어온) 인수 문자열과 형식 문자열을 넘겨 Args 인스턴스를 생성한 후 Args 인스턴스에다 인수 값을 질의한다. 다음 간단한 예를 살펴보자.

### 깔끔한 코드는 어떻게?

프로그래밍은 과학보다 공예에 가깝다. 
깨끗한 코드를 짜려면 먼저 지저분한 코드를 짠 뒤에 정리해야 한다. 
신입 프로그래머는 일단 프로그램이 돌아가는 프로그램을 목표로 잡는다. 그리고 프로그램이 돌아가면 다음 업무로 넘어간다. 경험이 풍부한 프로그래머라면 이런 행동이 자살 행위라는 사실을 잘 알 것이다.

### 점진적으로 개선하다

프로그램을 망치는 가장 좋은 방법 중 하나는 개선이라는 이름 아래 구조를 크게 뒤집는 행위다. 
그래서 주로 TDD 기법을 사용한다. TDD(Test-Drive Development)는 언제 어느 때라도 시스템이 돌아가야 한다는 원칙을 따른다.

그저 돌아가는 코드만으로는 부족하며, 돌아가는 코드가 심하게 망가지는 사례는 흔하다.  
언제나 최대한 깔끔하고 단순하게 정리하자. 절대로 썩어가게 방치하면 안 된다.