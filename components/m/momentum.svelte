<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7zde4bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:momentum" {...props}></Icon>
<style>
:global(.i7zde4bbi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m-7.5 0H7M4.5 8H8m-3.5 8H8");
}

</style>
