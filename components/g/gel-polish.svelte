<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l85868bsf"/><path class="ly8029b5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gel-polish" {...props}></Icon>
<style>
:global(.l85868bsf) {
  d: path("M5 21.5V10a7 7 0 0 1 14 0v11.5");
}

:global(.ly8029b5c) {
  d: path("M8 16V9.75a4 4 0 0 1 8 0V16Zm2.75-6.25V13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
