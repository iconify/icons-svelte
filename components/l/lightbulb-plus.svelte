<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwszuh8_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lightbulb-plus" {...props}></Icon>
<style>
:global(.lwszuh8_z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 15a6.5 6.5 0 1 1 5 0v2.5h-5ZM8 20.5h3.5M18 15v6m-3-3h6");
}

</style>
