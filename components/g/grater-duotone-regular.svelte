<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qvgbltbgf"/><path class="k_jhlzb9b"/><path class="ac5nw33zc"/><path class="a0tye7bdm"/><path class="yrhul2brc"/><path class="b4880zbbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grater-duotone-regular" {...props}></Icon>
<style>
:global(.a0tye7bdm) {
  d: path("M9 10h3");
}

:global(.ac5nw33zc) {
  d: path("M9 6a3 3 0 0 1 6 0");
}

:global(.b4880zbbv) {
  d: path("M9 18h3");
}

:global(.k_jhlzb9b) {
  d: path("M8 6h8c1 5 2 10 2 15H6c0 -5 1 -10 2 -15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvgbltbgf) {
  fill: currentColor;
  d: path("M8 6h8c1 5 2 10 2 15H6c0 -5 1 -10 2 -15");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yrhul2brc) {
  d: path("M12 14h3");
}

</style>
