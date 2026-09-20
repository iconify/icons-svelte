<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a46k8ibzd"/><path class="acyg6nb1v"/><path class="rf0c3ccmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bookshelf-speaker-outline-thin" {...props}></Icon>
<style>
:global(.a46k8ibzd) {
  d: path("M7 3v18h10V3Z");
}

:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rf0c3ccmk) {
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
