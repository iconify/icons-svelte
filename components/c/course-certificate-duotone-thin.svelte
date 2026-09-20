<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m3bzo61nx"/><path class="mmnpqegwb"/><path class="yxv11bcbk"/><path class="uxsptjbvt"/><path class="soorsrbax"/><path class="n8wwq96fg"/><path class="htfprqbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:course-certificate-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htfprqbon) {
  d: path("M15 17v4l2 -2 2 2v-4");
}

:global(.m3bzo61nx) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mmnpqegwb) {
  fill: currentColor;
  d: path("M14 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n8wwq96fg) {
  d: path("M14 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.soorsrbax) {
  d: path("M6 10h8");
}

:global(.uxsptjbvt) {
  d: path("M6 7h12");
}

:global(.yxv11bcbk) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
