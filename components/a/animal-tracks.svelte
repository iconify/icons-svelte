<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vj806eb0g"/><path class="mrsgfcc7l"/><path class="iz-138bdb"/><path class="htxu_cghl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:animal-tracks" {...props}></Icon>
<style>
:global(.htxu_cghl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 4.25h.01m2.24-.75h.01m2.24.75h.01");
}

:global(.iz-138bdb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 9.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0");
}

:global(.mrsgfcc7l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 13.25h.01M7 12.5h.01m2.24.75h.01");
}

:global(.vj806eb0g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 18.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
