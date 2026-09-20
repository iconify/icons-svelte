<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmq4fab-l"/><path class="kj1tfs36l"/><path class="a3ch5yb2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beer-mug-outline-thin" {...props}></Icon>
<style>
:global(.a3ch5yb2h) {
  d: path("M5 10h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kj1tfs36l) {
  d: path("M15 9c3 0 4 2 4 4s-1 4 -4 4");
}

:global(.pmq4fab-l) {
  d: path("M5 6h10v15H5Z");
}

</style>
