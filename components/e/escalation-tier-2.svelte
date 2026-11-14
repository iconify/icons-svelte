<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_3-t3b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:escalation-tier-2" {...props}></Icon>
<style>
:global(.i_3-t3b4r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 16.5h13.5A2.25 2.25 0 0 1 21 18.75A2.25 2.25 0 0 1 18.75 21H5.25A2.25 2.25 0 0 1 3 18.75a2.25 2.25 0 0 1 2.25-2.25m3.375-7h6.75a2.125 2.125 0 0 1 2.125 2.125a2.125 2.125 0 0 1-2.125 2.125h-6.75A2.125 2.125 0 0 1 6.5 11.625A2.125 2.125 0 0 1 8.625 9.5M8 6.75L12 3l4 3.75");
}

</style>
