<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="oy04mabob"/><path class="z7iu2hi9d"/><circle class="ffz4idt6b"/><path class="u7uwe924o"/><path class="f391oyb0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mail-spam" {...props}></Icon>
<style>
:global(.f391oyb0h) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 9h.01");
}

:global(.ffz4idt6b) {
  cx: 17.25px;
  cy: 6.75px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy04mabob) {
  width: 14px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.u7uwe924o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 4.75V7");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z7iu2hi9d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 15.5l3.15 2c.8.6 1.9.6 2.7 0l3.15-2");
}

</style>
