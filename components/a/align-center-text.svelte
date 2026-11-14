<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og9jum1ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:align-center-text" {...props}></Icon>
<style>
:global(.og9jum1ig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h17M7 10h10M3.5 14.5h17M8 19h8");
}

</style>
