<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tif2u2b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:distance-sign" {...props}></Icon>
<style>
:global(.tif2u2b_c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h14l4.5 5.25L17 13.5H3Zm7 10.5v8M6 6v4.5m0-2.25h9M15 6v4.5");
}

</style>
