<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdbg22bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cumulative-sum" {...props}></Icon>
<style>
:global(.qdbg22bba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 3.5H5l6.5 8l-6.5 8h8.084m4.916 2v-7m-3 3l3-3l3 3");
}

</style>
