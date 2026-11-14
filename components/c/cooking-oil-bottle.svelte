<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1tb-gltl"/><path class="exkjr1bte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cooking-oil-bottle" {...props}></Icon>
<style>
:global(.exkjr1bte) {
  d: path("M10 15c0-1.5 2-3 2-3s2 1.5 2 3c0 1.25-1 2-2 2s-2-.75-2-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n1tb-gltl) {
  d: path("M10 3.5h4V7c0 1.5 3 2 3 5v7a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-7c0-3 3-3.5 3-5Z");
}

</style>
