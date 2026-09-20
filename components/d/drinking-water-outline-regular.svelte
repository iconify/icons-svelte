<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hzi6sbb6g"/><path class="z3yxp_dum"/><path class="r182r524c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drinking-water-outline-regular" {...props}></Icon>
<style>
:global(.hzi6sbb6g) {
  d: path("M7 5v16h10V5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.z3yxp_dum) {
  d: path("m12 9 3 3a3 3 0 0 1 -6 0Z");
}

</style>
