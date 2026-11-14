<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm7e0pxct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ice-lolly" {...props}></Icon>
<style>
:global(.rm7e0pxct) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.5a5.5 5.5 0 0 1 11 0v10.25a1.25 1.25 0 0 1-2.5 0V16.5H6.5Zm5.5 8v5M9.5 7v5");
}

</style>
