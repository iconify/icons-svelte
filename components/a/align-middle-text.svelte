<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqs7nob6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:align-middle-text" {...props}></Icon>
<style>
:global(.oqs7nob6q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17m-17 17h17M6 10h12M6 14h8");
}

</style>
