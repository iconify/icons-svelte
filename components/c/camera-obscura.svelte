<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axmjv8e5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camera-obscura" {...props}></Icon>
<style>
:global(.axmjv8e5y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 3.5h11.5a1.75 1.75 0 0 1 1.75 1.75v13.5a1.75 1.75 0 0 1-1.75 1.75H8.25a1.75 1.75 0 0 1-1.75-1.75V5.25A1.75 1.75 0 0 1 8.25 3.5M2.5 10l19 9.5M2.5 14l19-9.5");
}

</style>
