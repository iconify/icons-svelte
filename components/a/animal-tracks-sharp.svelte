<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ixohv9m-v"/><path class="mrsgfcc7l"/><path class="lbs4q44tg"/><path class="htxu_cghl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:animal-tracks-sharp" {...props}></Icon>
<style>
:global(.htxu_cghl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 4.25h.01m2.24-.75h.01m2.24.75h.01");
}

:global(.ixohv9m-v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 18.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

:global(.lbs4q44tg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 9.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

:global(.mrsgfcc7l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 13.25h.01M7 12.5h.01m2.24.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
