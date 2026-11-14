<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdiui0zdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pi" {...props}></Icon>
<style>
:global(.sdiui0zdt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6h15M9 6v7c0 3-.75 5.25-2.75 6.5M15 6v11c0 1.5 1 2.5 3 2.25");
}

</style>
