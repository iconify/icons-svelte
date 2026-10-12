<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pkg4a5bjz"/><path class="vrdw_--oh"/><circle class="xuqu7-bnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gradient-descent" {...props}></Icon>
<style>
:global(.pkg4a5bjz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.75c2 9.75 5 15 9 15s7-5.25 9-15");
}

:global(.vrdw_--oh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 9.5h.01m1.99 3.25h.01");
}

:global(.xuqu7-bnz) {
  cx: 12px;
  cy: 14.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
