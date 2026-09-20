<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5fngqb7w"/><path class="q60f8gb4t"/><path class="m396qprpg"/><path class="jya260dbk"/><path class="kb54x75jw"/><path class="w0g35mhsz"/><path class="r-0o544te"/><path class="pfvjrtb4r"/><path class="p59zvybqt"/><path class="nk-dq3bmo"/><path class="som9nz4hy"/><path class="k04qs_b8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confetti-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jya260dbk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k04qs_b8d) {
  d: path("m9 18 3 3");
}

:global(.kb54x75jw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m396qprpg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 13 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nk-dq3bmo) {
  d: path("m16 14 3 3");
}

:global(.p59zvybqt) {
  d: path("m4 13 3 3");
}

:global(.pfvjrtb4r) {
  d: path("m15 5 3 3");
}

:global(.q60f8gb4t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r-0o544te) {
  d: path("m5 4 3 3");
}

:global(.som9nz4hy) {
  d: path("m10 10 3 3");
}

:global(.w0g35mhsz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w5fngqb7w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
