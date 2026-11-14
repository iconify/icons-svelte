<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kncoaw41v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aggregator" {...props}></Icon>
<style>
:global(.kncoaw41v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 4.5l8 7.5l-8 7.5M3 12h17.5M17 8.5l3.5 3.5l-3.5 3.5");
}

</style>
