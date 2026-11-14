<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hb80twj7w"/><path class="oj7xmybyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hearse-car" {...props}></Icon>
<style>
:global(.hb80twj7w) {
  d: path("M2.5 15.5v-9A1.5 1.5 0 0 1 4 5h10l3.5 4.5H20a1.5 1.5 0 0 1 1.5 1.5v4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oj7xmybyx) {
  d: path("M7 8h3a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 10 11H7a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 7 8m-2.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
