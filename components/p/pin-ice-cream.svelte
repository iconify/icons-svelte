<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm9hrpbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-ice-cream" {...props}></Icon>
<style>
:global(.gm9hrpbqb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h12l-6 10.5Zm0 0a3 3 0 0 1 1.25-4.25a5 5 0 0 1 9.5 0A3 3 0 0 1 18 11");
}

</style>
