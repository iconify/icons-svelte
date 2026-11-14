<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dptj25wza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:oven-mitt" {...props}></Icon>
<style>
:global(.dptj25wza) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8c0-3 3-4.5 6-4s4.5 3 4 5.5l-.5 2.5c2.5 0 3.5 2 2.5 4c-1.5 3-5 4.5-8 4.5H8Zm0 9h9");
}

</style>
