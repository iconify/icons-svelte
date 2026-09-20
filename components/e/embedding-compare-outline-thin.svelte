<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p0mfrtbaw"/><path class="vs9x-_bah"/><path class="hclo6jb2r"/><path class="ubmhydvvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embedding-compare-outline-thin" {...props}></Icon>
<style>
:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p0mfrtbaw) {
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
}

:global(.ubmhydvvx) {
  d: path("M8 19.5h8");
}

:global(.vs9x-_bah) {
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
}

</style>
