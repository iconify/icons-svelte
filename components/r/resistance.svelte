<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sucxkgb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:resistance" {...props}></Icon>
<style>
:global(.sucxkgb-j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12h2L9 8.5l2 7l2-7l2 7l1.5-3.5h2m-16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
