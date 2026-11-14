<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycvc9lb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-pool" {...props}></Icon>
<style>
:global(.ycvc9lb-f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 15.5V6A2.5 2.5 0 0 0 6 3.5m10.5 12V6A2.5 2.5 0 0 0 14 3.5M8.5 8h8m-8 4h8m-14 7q2.25-1.5 4.75 0Q9.5 20.5 12 19q2.25-1.5 4.75 0q2.25 1.5 4.75 0");
}

</style>
