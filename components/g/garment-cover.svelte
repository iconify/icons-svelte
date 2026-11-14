<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7w1_sbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garment-cover" {...props}></Icon>
<style>
:global(.k7w1_sbru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6h9l3 3v12.5h-15V9ZM12 6V5a1.5 1.5 0 1 0-1.5-1.5m1.5 5V20m0-9l2 1.75");
}

</style>
