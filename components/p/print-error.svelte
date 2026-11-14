<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="epk_oib4j"/><path class="h-3s31byv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:print-error" {...props}></Icon>
<style>
:global(.epk_oib4j) {
  d: path("M5.5 14.5h-1a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v3.5a2 2 0 0 1-2 2h-1V12h-7Zm0-7.5V4.5a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1V7");
}

:global(.h-3s31byv) {
  d: path("M5.5 12h7v7.5h-7ZM18 14.5v3.25m0 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
