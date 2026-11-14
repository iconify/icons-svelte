<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="slsd0y7tu"/><path class="ocvddkm9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-waste-sack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ocvddkm9i) {
  d: path("M8.5 18.5c0-4 3-7 7-7c0 4-3 7-7 7");
}

:global(.slsd0y7tu) {
  d: path("m4 8l1 12q.1 1.5 1.5 1.5h11q1.4 0 1.5-1.5l1-12Zm2.5 0c0-4.5 3.5-4.5 3.5 0m4 0c0-4.5 3.5-4.5 3.5 0");
}

</style>
