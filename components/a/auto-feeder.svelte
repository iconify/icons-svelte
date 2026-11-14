<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otftd_yjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:auto-feeder" {...props}></Icon>
<style>
:global(.otftd_yjp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10l-3.5 6v2.5h-3V9ZM3 14.5l2 6h14l2-6m-18 0h18");
}

</style>
