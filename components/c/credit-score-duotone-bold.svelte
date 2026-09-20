<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fgk90dbkb"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="x7bkced7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:credit-score-duotone-bold" {...props}></Icon>
<style>
:global(.fgk90dbkb) {
  fill: currentColor;
  d: path("m12 8 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x7bkced7s) {
  d: path("m12 8 2 2 -2 2 -2 -2Z");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
