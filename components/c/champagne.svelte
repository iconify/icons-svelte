<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2gz_bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:champagne" {...props}></Icon>
<style>
:global(.fo2gz_bdk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5h3V7c0 1.5 2.5 2.5 2.5 5v8a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 20v-8c0-2.5 2.5-3.5 2.5-5Zm0 3h3M8 14h8m-8 3.5h8M18.5 5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m0 4.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
