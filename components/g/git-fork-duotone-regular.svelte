<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="h8v3srbuf"/><path class="e4z2y8b_l"/><path class="pg7y1hu8s"/><path class="ymw3aibdo"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="t2l4a8b-m"/><path class="cq87c55hm"/><path class="erxvlz1uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-fork-duotone-regular" {...props}></Icon>
<style>
:global(.cq87c55hm) {
  d: path("m12 11 -5.5 5.5");
}

:global(.e4z2y8b_l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 11 -5.5 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.erxvlz1uk) {
  d: path("m12 11 5.5 5.5");
}

:global(.fg8libqda) {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h8v3srbuf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jz0b4rbqp) {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pg7y1hu8s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 11 5.5 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.st2iv5bfu) {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t2l4a8b-m) {
  d: path("M12 7.5V11");
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
