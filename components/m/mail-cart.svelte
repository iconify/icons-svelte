<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="on-yqybif"/><path class="jb91rib4p"/><rect class="ne2v47pna"/><path class="xs717bnyf"/><circle class="n67838b6u"/><circle class="pilcef9lb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mail-cart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jb91rib4p) {
  d: path("m9.75 4.75l2.75 2l2.75-2");
}

:global(.n67838b6u) {
  cx: 8.25px;
  cy: 20px;
  r: 1.25px;
}

:global(.ne2v47pna) {
  width: 14.5px;
  height: 7.5px;
  x: 5.25px;
  y: 8.75px;
  rx: 1.5px;
}

:global(.on-yqybif) {
  width: 7.5px;
  height: 5px;
  x: 8.75px;
  y: 3.75px;
  rx: 1px;
}

:global(.pilcef9lb) {
  cx: 16.75px;
  cy: 20px;
  r: 1.25px;
}

:global(.xs717bnyf) {
  d: path("M5.25 10.75H3V6m5.25 10.25v2.5m8.5-2.5v2.5");
}

</style>
