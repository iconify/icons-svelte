<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3p816jxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-phones" {...props}></Icon>
<style>
:global(.f3p816jxl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 2.5h2.25A4.375 4.375 0 0 1 17.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125V6.875A4.375 4.375 0 0 1 10.875 2.5m-.375 16h3");
}

</style>
