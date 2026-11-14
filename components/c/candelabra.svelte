<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg5r7ukln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:candelabra" {...props}></Icon>
<style>
:global(.wg5r7ukln) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6v3q0 4.5 6 4.5T18 9V6m-6 0v12m-4 3h8l-2-3h-4ZM6 3.25h.01m5.99 0h.01m5.99 0h.01");
}

</style>
