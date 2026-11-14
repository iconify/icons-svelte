<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sapgo9b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lira-sign" {...props}></Icon>
<style>
:global(.sapgo9b_j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5V20h1c4.75 0 8-3.25 8-8m-13-.5l8.5-3m-8.5 7l8.5-3");
}

</style>
