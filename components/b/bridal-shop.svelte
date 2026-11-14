<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpg945eyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bridal-shop" {...props}></Icon>
<style>
:global(.jpg945eyb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-11 9c-2 1-5.5 3.5-5.5 6h15c0-2.5-3.5-5-5.5-6Zm-.5-4c1 1 4 1 5 0l-.5 4h-4Z");
}

</style>
