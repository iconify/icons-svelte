<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4ym3z1fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:referee-stripes" {...props}></Icon>
<style>
:global(.a4ym3z1fu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-4 3.5-6.5 8-6.5s8 2.5 8 6.5M9 18v3m3-3v3m3-3v3");
}

</style>
