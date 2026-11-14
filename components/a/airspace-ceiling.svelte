<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvisa2yuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:airspace-ceiling" {...props}></Icon>
<style>
:global(.wvisa2yuo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18m-9 3l6 6h-3.5v7.5h-5V13H6Z");
}

</style>
