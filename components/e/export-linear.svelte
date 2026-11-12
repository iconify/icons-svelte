<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i2p-_hbwz"/><path class="x_hpbztkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:export-linear" {...props}></Icon>
<style>
:global(.i2p-_hbwz) {
  d: path("M4 12C4 16.4183 7.58172 20 12 20C16.4183 20 20 16.4183 20 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_hpbztkk) {
  stroke-linejoin: round;
  d: path("M12 14L12 4M9 7L12 4L15 7");
}

</style>
