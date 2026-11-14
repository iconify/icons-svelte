<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uet0sjbbr"/><path class="lsqxocc_d"/><path class="xkiburbct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:head-tracked-audio" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsqxocc_d) {
  d: path("M11.75 11.25zA1.75 1.75 0 0 1 13.5 13v1.5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 10 14.5V13a1.75 1.75 0 0 1 1.75-1.75M4 7.25a10.5 10.5 0 0 1 16 0");
}

:global(.uet0sjbbr) {
  d: path("M9 21.5v-3c-1.75-1.25-2.5-3.25-2.5-5.25C6.5 10 8.75 7.5 12 7.5c3 0 5.25 2 5.25 5.25l1.25 2.5q0 .75-.75.75h-.5v1.75c0 .75-.75 1.5-1.5 1.5h-1.5v2.25");
}

:global(.xkiburbct) {
  d: path("m17.5 7l2.5.25l.25-2.5");
}

</style>
