<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oasab4kca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:curb-stop" {...props}></Icon>
<style>
:global(.oasab4kca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14H15v5h6.5M7.25 9h1.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 8.75 14h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 7.25 9M8 9V5M5 5h6");
}

</style>
