<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ole2t0b7i"/><path class="rw80fnl0o"/><path class="a5f2adb3i"/><path class="gd2lzcb3p"/><path class="by13csbvw"/><path class="b0lbes7qy"/><path class="r-0o544te"/><path class="pfvjrtb4r"/><path class="p59zvybqt"/><path class="nk-dq3bmo"/><path class="som9nz4hy"/><path class="k04qs_b8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confetti-duotone-regular" {...props}></Icon>
<style>
:global(.a5f2adb3i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 13 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b0lbes7qy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 18 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.by13csbvw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gd2lzcb3p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k04qs_b8d) {
  d: path("m9 18 3 3");
}

:global(.nk-dq3bmo) {
  d: path("m16 14 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ole2t0b7i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p59zvybqt) {
  d: path("m4 13 3 3");
}

:global(.pfvjrtb4r) {
  d: path("m15 5 3 3");
}

:global(.r-0o544te) {
  d: path("m5 4 3 3");
}

:global(.rw80fnl0o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.som9nz4hy) {
  d: path("m10 10 3 3");
}

</style>
