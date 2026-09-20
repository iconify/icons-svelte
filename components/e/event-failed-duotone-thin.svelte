<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebovp7bpp"/><path class="c000x0vfn"/><path class="wbs7q7b-t"/><path class="v-jogvb5z"/><path class="weeetziwb"/><path class="qydoy8byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-failed-duotone-thin" {...props}></Icon>
<style>
:global(.c000x0vfn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 10 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ebovp7bpp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qydoy8byr) {
  d: path("m19 10 -5 5");
}

:global(.v-jogvb5z) {
  d: path("m10 6 -5 5h4l-5 5");
}

:global(.wbs7q7b-t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 10 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.weeetziwb) {
  d: path("m14 10 5 5");
}

</style>
