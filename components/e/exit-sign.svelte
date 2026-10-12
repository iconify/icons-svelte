<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="ceopgp_8f"/><path class="q6icwma0c"/><path class="gavuxkbkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:exit-sign" {...props}></Icon>
<style>
:global(.aqmj_4big) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.ceopgp_8f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 18.25V6h3.75v12.25");
}

:global(.gavuxkbkd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9l-1.25 4.25m-2-2.5L9.5 9l2 2l1.5.25m-4.75 2l2.25 1.5v3m-2.25-4.5L6.5 17.5");
}

:global(.q6icwma0c) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6.75h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
