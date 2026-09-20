<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u0qq5pehg"/><path class="spgjr37km"/><path class="rvm8j0zcc"/><path class="mddrthmzf"/><path class="xa0iemevq"/><path class="e9i5dwbzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distribution-shift-duotone-regular" {...props}></Icon>
<style>
:global(.e9i5dwbzy) {
  d: path("m10.5 13.5 3 -3");
}

:global(.mddrthmzf) {
  d: path("M3 16a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rvm8j0zcc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10.5 13.5 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.spgjr37km) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u0qq5pehg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa0iemevq) {
  d: path("M13 12a4 4 0 0 1 8 0");
}

</style>
