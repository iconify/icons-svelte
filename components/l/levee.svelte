<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kclsskbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:levee" {...props}></Icon>
<style>
:global(.kclsskbsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18h19m-13 0L13 6.5h4.5l4 11.5m-19-8q1.125-1.25 2.25 0T7 10m-4.5 4q1.125-1.25 2.25 0T7 14");
}

</style>
