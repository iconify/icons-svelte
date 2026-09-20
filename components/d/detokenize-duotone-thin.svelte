<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="po3ky8ubk"/><path class="bfyr8ibhk"/><path class="o2fuczn9e"/><path class="izqnth1lx"/><path class="pr8_q1bje"/><path class="askgmhbjk"/><path class="rwqrrdbai"/><path class="hh5c5wgme"/><path class="bfi7-obrv"/><path class="jgk39zb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detokenize-duotone-thin" {...props}></Icon>
<style>
:global(.askgmhbjk) {
  d: path("M3 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bfi7-obrv) {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

:global(.bfyr8ibhk) {
  fill: currentColor;
  d: path("M9 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hh5c5wgme) {
  d: path("M15 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izqnth1lx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11.5 12 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jgk39zb1b) {
  d: path("M4 18.5h16");
}

:global(.o2fuczn9e) {
  fill: currentColor;
  d: path("M15 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.po3ky8ubk) {
  fill: currentColor;
  d: path("M3 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pr8_q1bje) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rwqrrdbai) {
  d: path("M9 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
