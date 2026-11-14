<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pmzhhkmpk"/><path class="i7bi7hbey"/><path class="s6j3xwxah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:occupancy-certificate" {...props}></Icon>
<style>
:global(.i7bi7hbey) {
  d: path("M14.75 21.75v-7.5H21v7.5");
}

:global(.pmzhhkmpk) {
  d: path("M11.9 18H2.5V3.5h19v7.9M6 7.5h12M6 11h5.9");
}

:global(.s6j3xwxah) {
  d: path("m14.75 14.25l3.5 1.25v6.25h-3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
