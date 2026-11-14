<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8h8b_brj"/><path class="zc81ikodi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-kids-fashion" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8h8b_brj) {
  d: path("M9 2.5L4.5 4l-2 4.5L5 10l1-1.5v7q0 3.5 3.5 4v2h5v-2q3.5-.5 3.5-4v-7l1 1.5l2.5-1.5l-2-4.5L15 2.5C14 5 10 5 9 2.5");
}

:global(.zc81ikodi) {
  fill: currentColor;
  d: path("m12.367 10.244l.041.139a1.5 1.5 0 0 0 1.479 1.074l.145-.003a.383.383 0 0 1 .227.698l-.119.082a1.5 1.5 0 0 0-.565 1.739l.048.136a.383.383 0 0 1-.594.432l-.115-.088a1.5 1.5 0 0 0-1.828 0l-.115.088a.383.383 0 0 1-.594-.432l.048-.136a1.5 1.5 0 0 0-.565-1.739l-.119-.082a.383.383 0 0 1 .227-.698l.145.003a1.5 1.5 0 0 0 1.479-1.074l.041-.139a.383.383 0 0 1 .734 0");
}

</style>
