<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npbjr1b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ping-pong-ball" {...props}></Icon>
<style>
:global(.npbjr1b9h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 20h19m-19-10q3.5 7 6 7t3.5-3");
}

</style>
