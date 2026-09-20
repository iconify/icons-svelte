<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pqn6j-y8l"/><path class="l46grxbhs"/><path class="gl2wyfu4j"/><path class="uj1augdau"/><path class="d4rfzbb0c"/><path class="q686vz2zk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hangout-duotone-thin" {...props}></Icon>
<style>
:global(.d4rfzbb0c) {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gl2wyfu4j) {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l46grxbhs) {
  fill: currentColor;
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pqn6j-y8l) {
  fill: currentColor;
  d: path("M3 12v6h18v-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q686vz2zk) {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uj1augdau) {
  d: path("M3 12v6h18v-6Z");
}

</style>
