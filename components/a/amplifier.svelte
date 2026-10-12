<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="zep8nmydx"/><path class="ydv1z6bal"/><path class="zl5bs9bqu"/><circle class="ttf32rblh"/><circle class="mwwbpgbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:amplifier" {...props}></Icon>
<style>
:global(.mwwbpgbvl) {
  cx: 12px;
  cy: 14px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ttf32rblh) {
  cx: 12px;
  cy: 14px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ydv1z6bal) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7h14.5");
}

:global(.zep8nmydx) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.zl5bs9bqu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 4.9h.01m2.49 0h.01m2.49 0h.01");
}

</style>
