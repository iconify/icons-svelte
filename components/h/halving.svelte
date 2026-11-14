<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hivr20bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:halving" {...props}></Icon>
<style>
:global(.hivr20bef) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5a8.5 8.5 0 0 0 0 17Zm3 0a8.5 8.5 0 0 1 0 17Z");
}

</style>
