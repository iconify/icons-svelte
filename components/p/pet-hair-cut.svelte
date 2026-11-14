<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuktvtbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pet-hair-cut" {...props}></Icon>
<style>
:global(.zuktvtbka) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 6.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m0 10.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M8.5 8l12 8m-12 0l12-8M14 21c.5-2.5 2.5-2.5 3-1s2.5 1.5 3-1");
}

</style>
