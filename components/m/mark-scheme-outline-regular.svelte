<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="dg_gji4cg"/><path class="j9sqoabvp"/><path class="b-csqm2-o"/><path class="x0t1t4bmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mark-scheme-outline-regular" {...props}></Icon>
<style>
:global(.b-csqm2-o) {
  d: path("m7 15 2 2 3 -3");
}

:global(.dg_gji4cg) {
  d: path("m7 8 2 2 3 -3");
}

:global(.j9sqoabvp) {
  d: path("M15 9h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x0t1t4bmb) {
  d: path("M15 16h3");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
