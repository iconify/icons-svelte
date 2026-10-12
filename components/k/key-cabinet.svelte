<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><path class="iob5ejbxx"/><circle class="prtzy8bxe"/><path class="nas-b8bjc"/><circle class="s_dqu5bpt"/><path class="xlr9k7beb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:key-cabinet" {...props}></Icon>
<style>
:global(.g6ctus9qt) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iob5ejbxx) {
  d: path("M6.75 6.25h10.5");
}

:global(.nas-b8bjc) {
  d: path("M9 12.25v5.5h1.5");
}

:global(.prtzy8bxe) {
  cx: 9px;
  cy: 10.75px;
  r: 1.5px;
}

:global(.s_dqu5bpt) {
  cx: 15px;
  cy: 10.75px;
  r: 1.5px;
}

:global(.xlr9k7beb) {
  d: path("M15 12.25v5.5h1.5");
}

</style>
