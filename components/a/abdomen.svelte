<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0k-7ybvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:abdomen" {...props}></Icon>
<style>
:global(.b0k-7ybvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5c0 4-1.5 6.5-1.5 10s1 6.25 2.5 9m10-19c0 4 1.5 6.5 1.5 10s-1 6.25-2.5 9m-4.5-11h.01M8.5 16l2.75 5m4.25-5l-2.75 5");
}

</style>
