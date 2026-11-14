<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwboc2ioa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lake-view" {...props}></Icon>
<style>
:global(.nwboc2ioa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5H7c1 2.5 1.5 6.5 2 11m-2-11h14m-8 0v5m6-5v5m-8.5 0q1.25-1 2.5 0t2.5 0t2.5 0t2.5 0q.5-.5 1-.25M11 19.5q1.25-1 2.5 0t2.5 0t2.5 0t2.5 0");
}

</style>
