<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-4xkccyb"/><path class="r_4qgk6hg"/><path class="kwc83kvle"/><path class="q6qz5_ren"/><path class="jnx-0bmel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retention-policy-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnx-0bmel) {
  d: path("M19 17h2.5");
}

:global(.kwc83kvle) {
  d: path("M16 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.p-4xkccyb) {
  d: path("M2 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.q6qz5_ren) {
  d: path("M19 14.5V17");
}

:global(.r_4qgk6hg) {
  d: path("M4 9h10");
}

</style>
