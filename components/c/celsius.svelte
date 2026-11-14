<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlb9ivb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:celsius" {...props}></Icon>
<style>
:global(.wlb9ivb0n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.5v-8a2.5 2.5 0 0 1 5 0v8a4.5 4.5 0 1 1-5 0m8.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0M9.5 9v7");
}

</style>
