<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j32y5ibok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:package-open" {...props}></Icon>
<style>
:global(.j32y5ibok) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 12l8.5 3.5l8.5-3.5v7L12 22l-8.5-3Zm0 0L7 5.5L12 8l5-2.5l3.5 6.5");
}

</style>
