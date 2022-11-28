# 14.-odev

//say�n�n karesini al�p 5 ekleyen fonksiyon

#include<stdio.h>

int kare(int);

int main(void)
{
	int sayi;
	
	printf("sayiyi giriniz: ");
	scanf("%d" , &sayi);
	
	printf("sonuc: %d" , kare(sayi));
}

int kare(int x)
{
	int sonuc;
	
	sonuc=(x*x)+5;
	
	return sonuc;
}
