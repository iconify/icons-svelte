<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vdkk_bbqh"/><path class="jy2rzibrh"/><path class="fgqk6gbgn"/><path class="xpov22bfs"/><path class="acnb1hz5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:absent-duotone-thin" {...props}></Icon>
<style>
:global(.acnb1hz5q) {
  d: path("m22 14 -6 6");
}

:global(.fgqk6gbgn) {
  d: path("M2.4 16a6.6 6.6 0 0 1 13.2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jy2rzibrh) {
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vdkk_bbqh) {
  fill: currentColor;
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xpov22bfs) {
  d: path("m16 14 6 6");
}

</style>
