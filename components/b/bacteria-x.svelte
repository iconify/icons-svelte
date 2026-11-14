<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we3l8zc2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bacteria-x" {...props}></Icon>
<style>
:global(.we3l8zc2f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8.75 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-7.75 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m11 0l5 5m0-5l-5 5");
}

</style>
