<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0zu0bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-ohlc" {...props}></Icon>
<style>
:global(.jf0zu0bfr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5V17m7-14v12m7-7v13M2.75 8H5m0 6h2.25m2.5-2H12m0-6.5h2.25m2.5 5.5H19m0 7h2.25");
}

</style>
