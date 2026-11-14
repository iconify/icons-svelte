<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqcjesa6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:museum-rope-barrier" {...props}></Icon>
<style>
:global(.uqcjesa6t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5v14m14-14v14m-16 0h4m10 0h4M5 4h.01M19 4h.01M5 9q7 7 14 0");
}

</style>
