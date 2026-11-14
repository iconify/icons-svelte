<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4s8atbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:issue-escalated" {...props}></Icon>
<style>
:global(.x4s8atbsf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 19a8 8 0 1 1 8-8m-8 0h.01M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
