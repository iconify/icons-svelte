<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="sb4kn6-oq"/><path class="dpexgjbks"/><path class="lrp22rkqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chimta" {...props}></Icon>
<style>
:global(.dpexgjbks) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.47 6.04L7.5 21m6.03-14.96L16.5 21");
}

:global(.lrp22rkqr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 13h.01m12.49 0h.01");
}

:global(.sb4kn6-oq) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
