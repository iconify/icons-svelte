<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juymg2fta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:napkin-fold" {...props}></Icon>
<style>
:global(.juymg2fta) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21L2.5 9.5l4-5.5L12 2.5L17.5 4l4 5.5L14 21M4 21h16M6.5 4l2 8M12 2.5V12m5.5-8l-2 8");
}

</style>
