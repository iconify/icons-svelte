<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="azlzhub1j"/><path class="c19zehipj"/><path class="k6t-okb_f"/><path class="urk2115hi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:object-duotone-thin" {...props}></Icon>
<style>
:global(.azlzhub1j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c19zehipj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6t-okb_f) {
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
}

:global(.urk2115hi) {
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
}

</style>
