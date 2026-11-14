<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x8jtigbxp"/><path class="f-or10kgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:espresso-macchiato" {...props}></Icon>
<style>
:global(.f-or10kgf) {
  d: path("M16.5 11h1a2.5 2.5 0 0 1 0 5h-2m-8-6a3 3 0 0 1 3.25-3.5A2.75 2.75 0 0 1 13.5 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x8jtigbxp) {
  d: path("M5 10h11.5v4a5 5 0 0 1-5 5H10a5 5 0 0 1-5-5Z");
}

</style>
