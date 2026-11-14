<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcsaq7b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:performance-test" {...props}></Icon>
<style>
:global(.kcsaq7b7c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16a9 9 0 0 1 18 0m-9 0h.01M3 16h18m-9 0l4.5-6");
}

</style>
