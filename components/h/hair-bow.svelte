<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc5krrb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hair-bow" {...props}></Icon>
<style>
:global(.vc5krrb3u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 10.5L4.5 7c-1-.6-2 0-2 1v8c0 1 1 1.6 2 1l5.5-3.5m4-3L19.5 7c1-.6 2 0 2 1v8c0 1-1 1.6-2 1L14 13.5M10 10h4v4h-4Z");
}

</style>
