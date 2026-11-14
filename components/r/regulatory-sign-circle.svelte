<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5wn8b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:regulatory-sign-circle" {...props}></Icon>
<style>
:global(.dg5wn8b-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10a8 8 0 1 0 16 0a8 8 0 1 0-16 0m8 8v4M6.25 4.25l11.5 11.5");
}

</style>
