<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de5y7-rzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beauty-shelf" {...props}></Icon>
<style>
:global(.de5y7-rzd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 18h20M2.5 18v-8q0-2 1.5-2V5h1.5v3Q7 8 7 10v8m2.75-7h4.5v7h-4.5ZM17 18v-6l1.5-2V8H20v2l1.5 2v6");
}

</style>
