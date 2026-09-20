<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7z0vob4i"/><path class="mbt4yzbhr"/><path class="wy1_19byi"/><path class="gkgr58b-d"/><path class="tv7sb1bck"/><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:long-polling-duotone-regular" {...props}></Icon>
<style>
:global(.bxa1b1bso) {
  d: path("M6 5v14");
}

:global(.fr472ib_x) {
  d: path("m13 16 3 3 3 -3");
}

:global(.gkgr58b-d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i7z0vob4i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tv7sb1bck) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy1_19byi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7g1r9bby) {
  d: path("M16 5v14");
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
