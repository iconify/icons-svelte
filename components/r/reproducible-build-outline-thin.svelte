<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b0hkzgbgd"/><path class="o40l0bbgl"/><path class="a3fwgxb1c"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reproducible-build-outline-thin" {...props}></Icon>
<style>
:global(.a3fwgxb1c) {
  d: path("M9 11.5h6");
}

:global(.b0hkzgbgd) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o40l0bbgl) {
  d: path("M9 8.5h6");
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

</style>
