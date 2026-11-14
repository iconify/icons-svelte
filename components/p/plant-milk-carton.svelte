<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozpfiwb3l"/><path class="w3jqcbcjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plant-milk-carton" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozpfiwb3l) {
  d: path("m7 8l2-4.5h6L17 8v12.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5Zm0 0h10");
}

:global(.w3jqcbcjs) {
  d: path("M9.5 17.5c0-3.5 2-6 5-6c0 3.5-2 6-5 6");
}

</style>
