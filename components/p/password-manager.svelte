<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f71wfugrc"/><path class="v8rzpubvy"/><circle class="h_aonk51t"/><path class="lryu0zb7p"/><path class="niiog3b_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:password-manager" {...props}></Icon>
<style>
:global(.f71wfugrc) {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.h_aonk51t) {
  cx: 16.75px;
  cy: 11.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lryu0zb7p) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 11.25h.01");
}

:global(.niiog3b_x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 18.75v1.75m12-1.75v1.75");
}

:global(.v8rzpubvy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.25h.01m2.99 0h.01m2.99 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
