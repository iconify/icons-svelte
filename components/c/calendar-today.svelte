<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="p4y0o94ut"/><path class="sfq36tbjo"/><path class="lm782rbia"/><circle class="cret48b_z"/><path class="tgvveba2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:calendar-today" {...props}></Icon>
<style>
:global(.cret48b_z) {
  cx: 12px;
  cy: 15.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lm782rbia) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15.25h.01");
}

:global(.p4y0o94ut) {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.sfq36tbjo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

:global(.tgvveba2o) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 15.25h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
