<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i2p-_hbwz"/><path class="o7vxnob1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:import-linear" {...props}></Icon>
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

:global(.o7vxnob1s) {
  stroke-linejoin: round;
  d: path("M12 4L12 14M9 11L12 14L15 11");
}

</style>
