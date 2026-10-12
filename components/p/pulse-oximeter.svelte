<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fcajr2cvu"/><path class="ue6e7m9rq"/><path class="tr1qcbctt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pulse-oximeter" {...props}></Icon>
<style>
:global(.fcajr2cvu) {
  width: 14.5px;
  height: 13.5px;
  x: 6.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.5px;
}

:global(.tr1qcbctt) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7.75h.01m2.99 0h.01m2.99 0h.01");
}

:global(.ue6e7m9rq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25h12a1.75 1.75 0 0 1 0 3.5h-12Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
