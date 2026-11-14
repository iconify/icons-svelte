<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tr78iebwu"/><path class="cyayf_7wz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:city-hall" {...props}></Icon>
<style>
:global(.cyayf_7wz) {
  d: path("M10 21v-3.5a2 2 0 0 1 4 0V21m-8-6.5v3m12-3v3");
}

:global(.tr78iebwu) {
  d: path("M3 21v-9.5h5.5V6L12 2.75L15.5 6v5.5H21V21M2.5 21h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
