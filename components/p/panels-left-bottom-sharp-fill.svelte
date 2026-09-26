<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a6gbf1frc"/><path class="qjqiekbap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-left-bottom-sharp-fill" {...props}></Icon>
<style>
:global(.a6gbf1frc) {
  fill: currentColor;
  d: path("M3 3L9 3L9 21L3 21L3 3Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qjqiekbap) {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM9 3L9 21M9 15L21 15");
}

</style>
