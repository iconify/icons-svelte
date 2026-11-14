<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-c9gbb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reorder-down" {...props}></Icon>
<style>
:global(.m-c9gbb6s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6h10m-10 6h10m-10 6h10M5 4v16m-2.5-2.5L5 20l2.5-2.5");
}

</style>
