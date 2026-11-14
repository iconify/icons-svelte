<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjzvcdb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:avoid-sunlight" {...props}></Icon>
<style>
:global(.qjzvcdb-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0m5-8.5h.01m-.01 17h.01M3.5 12h.01m16.99 0h.01M18 6h.01M6 18h.01M6 6h.01M18 18h.01");
}

</style>
