<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztcsqe2ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ac-charging" {...props}></Icon>
<style>
:global(.ztcsqe2ts) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5h10v4a5 5 0 0 1-10 0Zm2.5-4v4m5-4v4m-10 13q1.875-3 3.75 0t3.75 0t3.75 0t3.75 0");
}

</style>
