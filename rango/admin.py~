#coding:utf-8
from django.contrib import admin
from rango.models import Category, Page
from rango.models import UserProfile

class CategoryAdmin(admin.ModelAdmin):
    prepopulated_fields = {'slug':('name',)}

admin.site.register(Category, CategoryAdmin)    #注册类装饰
admin.site.register(Page)
admin.site.register(UserProfile)
