<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mup1akhbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:denture-cup" {...props}></Icon>
<style>
:global(.mup1akhbm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 11l1 8.5A2 2 0 0 0 8 21h8a2 2 0 0 0 2-1.5l1-8.5M3.5 7.5h17V11h-17Zm5-5c0 2.75 7 2.75 7 0");
}

</style>
