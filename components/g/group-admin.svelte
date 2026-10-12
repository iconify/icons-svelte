<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="cy0xj6z4q"/><path class="wc528xbsj"/><circle class="hovlgbc0r"/><path class="opx14ob8g"/><circle class="mxe25qb8g"/><path class="ep0030bnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:group-admin" {...props}></Icon>
<style>
:global(.cy0xj6z4q) {
  cx: 5.25px;
  cy: 6.25px;
  r: 2.25px;
}

:global(.ep0030bnz) {
  d: path("M6.75 21.25h10.5a.75.75 0 0 0 .75-.75c0-2.9-2.6-4.75-6-4.75S6 17.6 6 20.5a.75.75 0 0 0 .75.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hovlgbc0r) {
  cx: 18.75px;
  cy: 6.25px;
  r: 2.25px;
}

:global(.mxe25qb8g) {
  cx: 12px;
  cy: 11.5px;
  r: 2px;
}

:global(.opx14ob8g) {
  d: path("M17 14h3.5a.75.75 0 0 0 .75-.75c0-1.9-1.1-3-2.5-3s-2.5 1.1-2.5 3A.75.75 0 0 0 17 14");
}

:global(.wc528xbsj) {
  d: path("M3.5 14H7a.75.75 0 0 0 .75-.75c0-1.9-1.1-3-2.5-3s-2.5 1.1-2.5 3a.75.75 0 0 0 .75.75");
}

</style>
