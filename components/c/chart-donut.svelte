<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir_h8d31n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-donut" {...props}></Icon>
<style>
:global(.ir_h8d31n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.5a8 8 0 1 0 8 8H15A4.5 4.5 0 1 1 10.5 9Zm2.75-2.75a8 8 0 0 1 8 8h-3.5a4.5 4.5 0 0 0-4.5-4.5Z");
}

</style>
