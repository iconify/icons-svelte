<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw7tex1hg"/><path class="plksdhbjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:milk-frother" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iw7tex1hg) {
  d: path("m6 12l1.5 9.5h9L18 12M6 12q1.5-1.75 3 0q1.5-1.75 3 0q1.5-1.75 3 0q1.5-1.75 3 0m-6-9.5zA1.5 1.5 0 0 1 13.5 4v2.5A1.5 1.5 0 0 1 12 8a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 12 2.5M12 8v6.75");
}

:global(.plksdhbjo) {
  d: path("M10 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
