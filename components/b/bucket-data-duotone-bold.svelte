<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j6br2vbzt"/><path class="dmzb83bqo"/><path class="xmuq15b2m"/><path class="sn5lf7ivh"/><path class="yp9owkodh"/><path class="zf7mx_7mn"/><path class="ufignx6hm"/><path class="cy34vrbps"/><path class="ooykrqbbx"/><path class="t3p_xpene"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bucket-data-duotone-bold" {...props}></Icon>
<style>
:global(.cy34vrbps) {
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dmzb83bqo) {
  fill: currentColor;
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j6br2vbzt) {
  fill: currentColor;
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ooykrqbbx) {
  d: path("M3 13v7h7v-7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sn5lf7ivh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3p_xpene) {
  d: path("M14 13v7h7v-7");
}

:global(.ufignx6hm) {
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xmuq15b2m) {
  fill: currentColor;
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yp9owkodh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zf7mx_7mn) {
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
