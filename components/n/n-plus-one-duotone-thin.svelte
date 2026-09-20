<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eff5yibna"/><path class="stexy9brj"/><path class="q68-sbrnw"/><path class="enu3nubgv"/><path class="rpp4spbxo"/><path class="pq9ly31-r"/><path class="iup9trbmr"/><path class="w92rm08yv"/><path class="t0-mwc0xy"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:n-plus-one-duotone-thin" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.eff5yibna) {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.enu3nubgv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.q68-sbrnw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16v-6h16v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rpp4spbxo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.stexy9brj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.w92rm08yv) {
  d: path("M4 16v-6h16v6");
}

</style>
