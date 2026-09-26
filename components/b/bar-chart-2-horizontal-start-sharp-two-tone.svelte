<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dog_d0bzi"/><path class="kspa2rbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-2-horizontal-start-sharp-two-tone" {...props}></Icon>
<style>
:global(.dog_d0bzi) {
  stroke-opacity: 0.4;
  d: path("M1 4L23 4M1 12L16 12");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kspa2rbdv) {
  d: path("M1 20L9 20");
}

</style>
