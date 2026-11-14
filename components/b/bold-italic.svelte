<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akzp3rb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bold-italic" {...props}></Icon>
<style>
:global(.akzp3rb5r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5h6A4 4 0 0 1 13 12h1a4 4 0 0 1-1.5 7.5h-7ZM7 12h6");
}

</style>
