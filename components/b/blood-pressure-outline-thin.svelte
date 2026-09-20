<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhkpzybsm"/><path class="dgzuelb_e"/><path class="sebrrz16i"/><path class="z9ywnzvgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blood-pressure-outline-thin" {...props}></Icon>
<style>
:global(.bhkpzybsm) {
  d: path("M2 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.dgzuelb_e) {
  d: path("M2 11h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sebrrz16i) {
  d: path("M14 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.z9ywnzvgb) {
  d: path("M18 12v3h3");
}

</style>
