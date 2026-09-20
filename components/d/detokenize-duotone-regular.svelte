<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="po3ky8ubk"/><path class="bfyr8ibhk"/><path class="o2fuczn9e"/><path class="j868g7ged"/><path class="qbg7wtb9n"/><path class="askgmhbjk"/><path class="rwqrrdbai"/><path class="hh5c5wgme"/><path class="bfi7-obrv"/><path class="jgk39zb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detokenize-duotone-regular" {...props}></Icon>
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

:global(.j868g7ged) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 11.5 12 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jgk39zb1b) {
  d: path("M4 18.5h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

:global(.qbg7wtb9n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rwqrrdbai) {
  d: path("M9 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
