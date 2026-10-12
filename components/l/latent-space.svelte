<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txr5qfbtf"/><circle class="cx8dycbip"/><circle class="aru5o0b-z"/><circle class="vfirqw8mn"/><circle class="beel-rkvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:latent-space" {...props}></Icon>
<style>
:global(.aru5o0b-z) {
  cx: 17.5px;
  cy: 5.75px;
  r: 1.25px;
}

:global(.beel-rkvu) {
  cx: 18px;
  cy: 11px;
  r: 1.25px;
}

:global(.cx8dycbip) {
  cx: 13.25px;
  cy: 9.75px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.txr5qfbtf) {
  d: path("M8 15.5V3.25M8 15.5h12.75M8 15.5l-5 5");
}

:global(.vfirqw8mn) {
  cx: 12.75px;
  cy: 4.5px;
  r: 1.25px;
}

</style>
