<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsuht_b8c"/><path class="i8o-lgigj"/><path class="xoaby-lkq"/><path class="l54ldrb1d"/><path class="vj9tr5bki"/><path class="acyg6nb1v"/><path class="ctdwryy5l"/><path class="d5_p0tpur"/><path class="ciwbnxb_b"/><path class="jnysnpbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fork-duotone-thin" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ciwbnxb_b) {
  d: path("M3 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ctdwryy5l) {
  d: path("M10.5 9.5 6 14");
}

:global(.d5_p0tpur) {
  d: path("M13.5 9.5 18 14");
}

:global(.fsuht_b8c) {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i8o-lgigj) {
  fill: currentColor;
  d: path("M3 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jnysnpbhj) {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l54ldrb1d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 9.5 6 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vj9tr5bki) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 9.5 18 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xoaby-lkq) {
  fill: currentColor;
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
