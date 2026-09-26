<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="epm6m9bbq"/><path class="k4zpahbdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-sharp-two-tone" {...props}></Icon>
<style>
:global(.epm6m9bbq) {
  stroke-opacity: 0.4;
  d: path("M4 8L4 23M12 1L12 23");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k4zpahbdz) {
  d: path("M20 15L20 23");
}

</style>
