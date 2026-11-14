<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdyqkm27t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:like-burst" {...props}></Icon>
<style>
:global(.mdyqkm27t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17.75s-5-3-5-6.25C7 10 8.25 8.75 9.75 8.75c1 0 1.75.75 2.25 1.5c.5-.75 1.5-1.5 2.25-1.5C15.75 8.75 17 10 17 11.5c0 3.25-5 6.25-5 6.25M12 3v2.5M5.5 5L7 6.5M18.5 5L17 6.5M3 12h2m16 0h-2");
}

</style>
