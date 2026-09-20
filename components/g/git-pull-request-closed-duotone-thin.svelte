<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qecovn3xi"/><path class="jz0b4rbqp"/><path class="acai3yb8w"/><path class="w3yo9mbxt"/><path class="nhpugqpma"/><path class="tcdrhgblz"/><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="jgg5ctbbh"/><path class="kk_08-buh"/><path class="qn318hakm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-pull-request-closed-duotone-thin" {...props}></Icon>
<style>
:global(.acai3yb8w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fg8libqda) {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgg5ctbbh) {
  d: path("m15.5 16.5 5 5");
}

:global(.jz0b4rbqp) {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k5nz3bcao) {
  d: path("M6 7.5v9");
}

:global(.kk_08-buh) {
  d: path("m20.5 16.5 -5 5");
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nhpugqpma) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20.5 16.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qecovn3xi) {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qn318hakm) {
  d: path("M18 14V9h-6L9 6");
}

:global(.tcdrhgblz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14V9h-6L9 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w3yo9mbxt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15.5 16.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
