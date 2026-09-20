<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bw1t57bti"/><path class="u-6h9nqio"/><path class="k8y9e5sub"/><path class="hwufvfb8q"/><path class="veo4_yb-t"/><path class="mkaclw6aw"/><path class="fkf_gcbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gym-duotone-thin" {...props}></Icon>
<style>
:global(.bw1t57bti) {
  fill: currentColor;
  d: path("M3 20v-8l9 -9 9 9v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fkf_gcbra) {
  d: path("M10 15h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwufvfb8q) {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

:global(.k8y9e5sub) {
  fill: currentColor;
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mkaclw6aw) {
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.u-6h9nqio) {
  fill: currentColor;
  d: path("M6 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.veo4_yb-t) {
  d: path("M6 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
