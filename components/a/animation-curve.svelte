<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjkpwtbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:animation-curve" {...props}></Icon>
<style>
:global(.hjkpwtbhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 18.5c5.5 0 4.5-13 10-13m-11 12za1.414 1.414 0 0 1 0 2a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 1 0-2a1.414 1.414 0 0 1 2 0m14-13za1.414 1.414 0 0 1 0 2a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 1 0-2a1.414 1.414 0 0 1 2 0");
}

</style>
