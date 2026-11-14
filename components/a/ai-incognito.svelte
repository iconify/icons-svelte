<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="empgqy1hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-incognito" {...props}></Icon>
<style>
:global(.empgqy1hd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 10l2-5.5h9l2 5.5M3 10h18M5 16.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m9 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-4-.5h4");
}

</style>
