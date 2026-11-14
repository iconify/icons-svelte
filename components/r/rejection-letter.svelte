<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ywpdmq4md"/><path class="w15bunbwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rejection-letter" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w15bunbwm) {
  d: path("m3 6l8.75 6.5L20.5 6m-5 9.5l5 5m0-5l-5 5");
}

:global(.ywpdmq4md) {
  d: path("M13.6 17.5H2.5v-13H21v7.6");
}

</style>
