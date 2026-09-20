<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bw0_0vbfj"/><path class="fz6tc-4je"/><path class="qcb83wbuk"/><path class="p925lhbvr"/><path class="dhm9wy0nm"/><path class="o8scmcc3i"/><path class="uxy9sxbfx"/><path class="o50_pabww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:best-of-n-duotone-thin" {...props}></Icon>
<style>
:global(.bw0_0vbfj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dhm9wy0nm) {
  d: path("M3 5h10");
}

:global(.fz6tc-4je) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o50_pabww) {
  d: path("m16 12 2 2 4 -4");
}

:global(.o8scmcc3i) {
  d: path("M3 12h10");
}

:global(.p925lhbvr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 12 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qcb83wbuk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uxy9sxbfx) {
  d: path("M3 19h10");
}

</style>
