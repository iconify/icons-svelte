<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itx429s_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mulch-plant" {...props}></Icon>
<style>
:global(.itx429s_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0m8.5-2.5V4m0 6c0-4 3-6 7-6c0 4-3 6-7 6m0 3.5c0-3-2.5-5-6.5-5c0 3.5 2.5 5 6.5 5");
}

</style>
