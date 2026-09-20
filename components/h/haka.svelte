<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGrUn1ddWd)" class="kn9wkab8y"/><path fill="url(#SVGVSqzUdBO)" class="kmfg09b5r"/><path fill="url(#SVGj4w6TcSJ)" class="ryz2b8v5r"/><defs><linearGradient id="SVGrUn1ddWd" x1="20.19" x2="3.256" y1="5.259" y2="5.259" gradientUnits="userSpaceOnUse"><stop class="mme4rdgfu"/><stop offset=".47" class="im_xjub1l"/><stop offset="1" class="h8dpxis2p"/></linearGradient><linearGradient id="SVGVSqzUdBO" x1="20.468" x2="4.167" y1="10.291" y2="11.006" gradientUnits="userSpaceOnUse"><stop class="eejlqibqn"/><stop offset=".51" class="bw0dm17lz"/><stop offset="1" class="fl0_a5b2u"/></linearGradient><linearGradient id="SVGj4w6TcSJ" x1="13.778" x2="20.415" y1="20.748" y2="13.524" gradientUnits="userSpaceOnUse"><stop class="e0dmdeb1a"/><stop offset=".46" class="w9ufxyb6i"/><stop offset="1" class="eejlqibqn"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:haka" {...props}></Icon>
<style>
:global(.bw0dm17lz) {
  stop-color: var(--svg-color--402284, #402284);
}

:global(.e0dmdeb1a) {
  stop-color: var(--svg-color--3a3781, #3a3781);
}

:global(.eejlqibqn) {
  stop-color: var(--svg-color--17b372, #17b372);
}

:global(.fl0_a5b2u) {
  stop-color: var(--svg-color--1caddb, #1caddb);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h8dpxis2p) {
  stop-color: var(--svg-color--7826f4, #7826f4);
}

:global(.im_xjub1l) {
  stop-color: var(--svg-color--d41b81, #d41b81);
}

:global(.kmfg09b5r) {
  d: path("M12.545 20.982A8.997 8.997 0 0 0 19.41 6.893v1.403h-.99q.149.261.275.53h.715V12a7.41 7.41 0 0 1-5.865 7.25zm-.28.01v-1.587a7 7 0 0 1-.53 0v1.588q.265.007.53 0m-.81-.01A8.997 8.997 0 0 1 4.59 6.893v5.108a7.41 7.41 0 0 0 5.865 7.25zm7.41-14.803A9 9 0 0 0 12 3.003A8.97 8.97 0 0 0 5.14 6.18h2.277A7.37 7.37 0 0 1 12 4.59a7.37 7.37 0 0 1 4.583 1.588z");
}

:global(.kn9wkab8y) {
  d: path("M11.47 6.708H5.12v3.704h3.175v3.24l1.059 2.053V9.354H6.178V7.766h4.234v10.585l1.059 2.032zm7.41 2.646v1.058h-2.646v3.15l-.042.02l.042.006l-2.646 4.763l-1.059 2.117V6.708h6.351v1.058h-5.292v8.643l1.588-2.954V9.354z");
}

:global(.mme4rdgfu) {
  stop-color: var(--svg-color--4fb585, #4fb585);
}

:global(.ryz2b8v5r) {
  d: path("M14.111 20.749a9 9 0 0 0 6.828-7.727a24 24 0 0 1-1.673.428a7.42 7.42 0 0 1-5.15 5.653v1.64z");
}

:global(.w9ufxyb6i) {
  stop-color: var(--svg-color--c03281, #c03281);
}

</style>
