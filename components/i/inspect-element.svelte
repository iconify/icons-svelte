<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slz38tbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:inspect-element" {...props}></Icon>
<style>
:global(.slz38tbob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.3 18H2.5V2.5H18v8.8M14 17a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25l2.25 2.25");
}

</style>
