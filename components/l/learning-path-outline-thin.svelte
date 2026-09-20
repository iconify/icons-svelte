<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5sglqb0f"/><path class="h3z56pbbf"/><path class="z_si_bbvo"/><path class="a51oytv8p"/><path class="pv_diebju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:learning-path-outline-thin" {...props}></Icon>
<style>
:global(.a51oytv8p) {
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h3z56pbbf) {
  d: path("M2 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h5sglqb0f) {
  d: path("m4 20 5 -5v-5l5 -5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pv_diebju) {
  d: path("M17 21h4");
}

:global(.z_si_bbvo) {
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
