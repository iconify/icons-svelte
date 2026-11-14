<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irf6yox7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cloth-nappy" {...props}></Icon>
<style>
:global(.irf6yox7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5h18v5q-5 2-6 9H9q-1-7-6-9Zm0 3h18");
}

</style>
