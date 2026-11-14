<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9m853byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:erhu" {...props}></Icon>
<style>
:global(.z9m853byt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5V15m-3 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0M6 4.5h2.5M6 7.5h2.5m5 13.5q6-8 3.5-17.5");
}

</style>
