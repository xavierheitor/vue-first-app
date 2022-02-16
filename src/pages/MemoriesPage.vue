<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>All memories</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <h2>Theese are my memories</h2>
        </ion-content>
    </ion-page>
</template>

<script>
import { IonPage, IonHeader, IonTitle, IonContent, IonToolbar } from '@ionic/vue';

export default {
    components: {
        IonPage,
        IonHeader,
        IonTitle,
        IonContent,
        IonToolbar
    }
}
</script>