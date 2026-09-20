<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="its1e1bwq"/><path class="h949zhbdz"/><path class="jd4p1lf8b"/><path class="ppivcbbzp"/><path class="x3k3riida"/><path class="hehuylblo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rebase-duotone-regular" {...props}></Icon>
<style>
:global(.h949zhbdz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 14 6 -6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hehuylblo) {
  d: path("m16 5 3 3 -3 3");
}

:global(.its1e1bwq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jd4p1lf8b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.x3k3riida) {
  d: path("m5 14 6 -6h8");
}

</style>
