<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="omkt26sjc"/><path class="dd_6j-l0z"/><path class="fxlibkbyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:anxious" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.dd_6j-l0z) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

:global(.fxlibkbyr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 16.75c.75-.75 1.6-1.1 2.5-1.1s1.75.35 2.5 1.1m3-6c.75 1.1 1.25 1.85 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.65.5-1.4 1.25-2.5");
}

:global(.omkt26sjc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.75L9.75 7.5m4.5 0L17 8.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
