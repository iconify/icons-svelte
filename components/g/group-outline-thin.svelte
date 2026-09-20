<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/><path class="jlsc9oajw"/><path class="h3yzlbw2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:group-outline-thin" {...props}></Icon>
<style>
:global(.fsv7g_bbj) {
  d: path("M9 21H3v-6");
}

:global(.h3yzlbw2w) {
  d: path("M14 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlsc9oajw) {
  d: path("M6 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

:global(.l6e2wzbuh) {
  d: path("M3 9V3h6");
}

:global(.ne_b8wtyo) {
  d: path("M21 15v6h-6");
}

:global(.qtj-xccdg) {
  d: path("M15 3h6v6");
}

</style>
