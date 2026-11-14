<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucqwwcbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:jhalmuri" {...props}></Icon>
<style>
:global(.ucqwwcbuc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19 8.5l-7 10l-7-10c0-3 2.5-4 4-3c1-3 5-3 6 0c1.5-1 4 0 4 3m-14 0h14M10.5 21l1.5-2.5l1.5 2.5Z");
}

</style>
