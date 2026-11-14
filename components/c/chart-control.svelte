<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9k-d8yjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-control" {...props}></Icon>
<style>
:global(.e9k-d8yjc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 12.5l3-3l3 5l3-6l3 7l3-5.5l4 3m-19-8.5H5m2.75 0h2.5m2.75 0h2.5m2.75 0h3.25m-19 15H5m2.75 0h2.5m2.75 0h2.5m2.75 0h3.25");
}

</style>
