<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5ypyoehl"/><path class="l12_cmb5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-horizontal-end-two-tone" {...props}></Icon>
<style>
:global(.i5ypyoehl) {
  stroke-opacity: 0.4;
  d: path("M2 12L22 12M9 20L22 20");
}

:global(.l12_cmb5r) {
  d: path("M16 4L22 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
