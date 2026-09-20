<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mn-a1zb6m"/><path class="e2kgfl2ea"/><path class="s25-orfog"/><path class="jv3d31_7h"/><path class="x1_r36phd"/><path class="jkjmjem6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:follow-back-outline-regular" {...props}></Icon>
<style>
:global(.e2kgfl2ea) {
  d: path("M2 15a3 3 0 0 1 6 0");
}

:global(.jkjmjem6y) {
  d: path("m11 10 -2 2 2 2");
}

:global(.jv3d31_7h) {
  d: path("M16 15a3 3 0 0 1 6 0");
}

:global(.mn-a1zb6m) {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s25-orfog) {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

</style>
