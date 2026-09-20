<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ajq5z5bvz"/><path class="vib1b5bye"/><path class="ve1q15bsq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:course-module-outline-regular" {...props}></Icon>
<style>
:global(.ajq5z5bvz) {
  d: path("M4 9h11v11H4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ve1q15bsq) {
  d: path("m15 9 5 -5v11l-5 5");
}

:global(.vib1b5bye) {
  d: path("m4 9 5 -5h11l-5 5");
}

</style>
