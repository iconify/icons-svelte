<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lksx1acly"/><path class="ovdeippwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eco-leaf-bolt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lksx1acly) {
  d: path("M4 20C3 11 8 3.5 20 3.5C20.5 15 14 21 4 20");
}

:global(.ovdeippwl) {
  d: path("M11.617 8.844L9.55 11.6a.875.875 0 0 0 .7 1.4a1.404 1.404 0 0 1 1.37 1.708l-.12.542a.497.497 0 0 0 .883.406L14.45 12.9a.875.875 0 0 0-.7-1.4a1.404 1.404 0 0 1-1.37-1.708l.12-.542a.497.497 0 0 0-.883-.406");
}

</style>
