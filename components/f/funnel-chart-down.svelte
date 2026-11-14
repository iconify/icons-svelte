<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk3ff5spl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:funnel-chart-down" {...props}></Icon>
<style>
:global(.kk3ff5spl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.478 18.952L9 20.5V11L3 3.5h16L13 11v5.595m5-2.095v7m-3-3l3 3l3-3");
}

</style>
