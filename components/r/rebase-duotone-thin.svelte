<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="atmhlzoyy"/><path class="xn5xrlbtk"/><path class="ppivcbbzp"/><path class="x3k3riida"/><path class="hehuylblo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rebase-duotone-thin" {...props}></Icon>
<style>
:global(.atmhlzoyy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 14 6 -6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hehuylblo) {
  d: path("m16 5 3 3 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrmo-yb4e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.x3k3riida) {
  d: path("m5 14 6 -6h8");
}

:global(.xn5xrlbtk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
