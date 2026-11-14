<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiyq5cc7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plastic-carrier-bag" {...props}></Icon>
<style>
:global(.xiyq5cc7q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h3.5V6a3.5 3.5 0 0 0 7 0V3.5H19v15a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 18.5ZM9 14h6");
}

</style>
