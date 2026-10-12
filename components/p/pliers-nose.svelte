<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipeesrb1t"/><circle class="adcsmfg4s"/><path class="g5aa34bpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pliers-nose" {...props}></Icon>
<style>
:global(.adcsmfg4s) {
  cx: 12px;
  cy: 11.75px;
  r: 2px;
}

:global(.g5aa34bpo) {
  d: path("M10.25 13.25Q7 16 3.75 21.25H8q1.25-4.25 3.5-7.5Zm3.5 0q3.25 2.75 6.5 8H16q-1.25-4.25-3.5-7.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipeesrb1t) {
  d: path("M9.75 10.5L12 2.75l2.25 7.75");
}

</style>
