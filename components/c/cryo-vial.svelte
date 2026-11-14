<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrehzkdxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cryo-vial" {...props}></Icon>
<style>
:global(.qrehzkdxz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.5h4.5A1.75 1.75 0 0 1 13 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 5 4.75v-.5A1.75 1.75 0 0 1 6.75 2.5M6 6.5V18a3 3 0 0 0 6 0V6.5M6 11h6m5.5 4v6M15 16.5l5 3m-5 0l5-3");
}

</style>
