<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xgb7fdcoy"/><path class="pko_rh_1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deposit-lump-sum" {...props}></Icon>
<style>
:global(.pko_rh_1b) {
  d: path("M14.75 14.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xgb7fdcoy) {
  d: path("M2.5 9h19v11h-19ZM4 9V7h16v2M5.5 7V5h13v2M8 5v15m3-15v15");
}

</style>
