<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i0tm_6p0q"/><path class="bvpe1-nac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-2-horizontal-end-two-tone" {...props}></Icon>
<style>
:global(.bvpe1-nac) {
  d: path("M16 20L22 20");
}

:global(.i0tm_6p0q) {
  stroke-opacity: 0.4;
  d: path("M2 4L22 4M9 12L22 12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
