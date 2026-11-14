<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwhwt3blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bench-backless" {...props}></Icon>
<style>
:global(.fwhwt3blv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 10H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 7m1.5 3v7m13-7v7m-13-3h13");
}

</style>
