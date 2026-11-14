<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljddvif1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boxing-robe" {...props}></Icon>
<style>
:global(.ljddvif1b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5L12 9l3-5.5l4.5 2l2 6.5l-4 .5V21h-11v-8.5l-4-.5l2-6.5ZM12 9v12m-5.5-6.5h11");
}

</style>
