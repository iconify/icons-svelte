<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbp1cmbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:footfall-up" {...props}></Icon>
<style>
:global(.qbp1cmbfz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M3.5 17v-3a4.5 4.5 0 0 1 9 0v3m5.5 1V5m-2.5 2.5L18 5l2.5 2.5");
}

</style>
