<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0abv-hss"/><path class="x-_m28bco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:engraving-service" {...props}></Icon>
<style>
:global(.q0abv-hss) {
  d: path("M11.8 18.5H2.5v-14h19v7.3M5 7h.01M19 7h.01M5 16h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-_m28bco) {
  d: path("M5.5 13C7 9 8.75 9 8.75 11.5s1.5 2.5 2.5.5s2.5-2 2.5 0c0 1.5 1.5 1.5 2.75.25m-2.25 9.5l.25-2.5L19.75 14L22 16.25l-5.25 5.25Zm3.5-5.75L20 18.25");
}

</style>
