<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj29qdbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:catalyst" {...props}></Icon>
<style>
:global(.hj29qdbjm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h17.5m-5-4.5l5 4.5m-1 5.5L16 18h4l-3.5 3.5");
}

</style>
