<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yde3gobvh"/><path class="tww2l34ri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-audio" {...props}></Icon>
<style>
:global(.tww2l34ri) {
  d: path("M3 13h4v6H3Zm14 0h4v6h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yde3gobvh) {
  d: path("M4.5 14v-2a7.5 7.5 0 0 1 15 0v2");
}

</style>
