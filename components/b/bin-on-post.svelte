<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1vuljhxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bin-on-post" {...props}></Icon>
<style>
:global(.y1vuljhxg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16M9.5 6V4.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V6m-9 0l1 9A1.5 1.5 0 0 0 8 16.5h8a1.5 1.5 0 0 0 1.5-1.5l1-9M10 9v4.5M14 9v4.5m-2 3v5m-3.5 0h7");
}

</style>
