<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqzo8ncai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mine-cage" {...props}></Icon>
<style>
:global(.hqzo8ncai) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7m-3.5 0v3M4.5 9L12 5.5L19.5 9m-15 0h15v12h-15Zm5 0v12m5-12v12");
}

</style>
