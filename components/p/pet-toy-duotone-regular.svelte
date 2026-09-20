<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aqyofsnqg"/><path class="ka-mlwp5y"/><path class="kf5i1zqrr"/><path class="k3qdczbds"/><path class="im38brk4q"/><path class="uxyzhxvwz"/><path class="quv6fgbpo"/><path class="ezl2ndbvl"/><path class="oumlmtbql"/><path class="ap8hfz6rg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-toy-duotone-regular" {...props}></Icon>
<style>
:global(.ap8hfz6rg) {
  d: path("M16 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.aqyofsnqg) {
  fill: currentColor;
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ezl2ndbvl) {
  d: path("M4 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.im38brk4q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k3qdczbds) {
  fill: currentColor;
  d: path("M16 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ka-mlwp5y) {
  fill: currentColor;
  d: path("M4 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kf5i1zqrr) {
  fill: currentColor;
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oumlmtbql) {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.quv6fgbpo) {
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
