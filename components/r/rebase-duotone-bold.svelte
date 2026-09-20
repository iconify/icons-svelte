<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="naa67qbfw"/><path class="jit-l8qct"/><path class="nt8-ftbgq"/><path class="ppivcbbzp"/><path class="x3k3riida"/><path class="hehuylblo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rebase-duotone-bold" {...props}></Icon>
<style>
:global(.hehuylblo) {
  d: path("m16 5 3 3 -3 3");
}

:global(.jit-l8qct) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 14 6 -6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naa67qbfw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nt8-ftbgq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x3k3riida) {
  d: path("m5 14 6 -6h8");
}

</style>
