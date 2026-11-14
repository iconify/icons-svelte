<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lstwonb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:building-crane-toy" {...props}></Icon>
<style>
:global(.lstwonb2q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5v15h4.5v-15M3 6.5h18m-16 0l2.25-4l5.75 4m5 0V11a1.5 1.5 0 0 1-3 0m1.25 5h2.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 16.25 16");
}

</style>
