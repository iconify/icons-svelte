<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouwv3zbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gym-shorts" {...props}></Icon>
<style>
:global(.ouwv3zbic) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h16v3.5L21.5 19h-8L12 13.5L10.5 19h-8L4 8.5Zm0 3.5h16m-2.75 0l1.5 10.5");
}

</style>
