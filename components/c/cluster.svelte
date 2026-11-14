<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgl91nb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cluster" {...props}></Icon>
<style>
:global(.hgl91nb7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h6v6H9Zm-6.5 13h6v6h-6Zm13 0h6v6h-6Zm-7 3h7M10 8.5l-3.5 7m7.5-7l3.5 7");
}

</style>
