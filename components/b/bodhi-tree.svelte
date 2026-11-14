<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y31v84pyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bodhi-tree" {...props}></Icon>
<style>
:global(.y31v84pyo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5c-3 0-3-5 0-5C5 4 10 2 12.5 4c2.5-2 8-.5 7 4.5c3 .5 2.5 5-.5 5Zm5.5 0v4l-3 3m6-7v4l3 3");
}

</style>
