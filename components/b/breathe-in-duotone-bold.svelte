<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6e_qy8ax"/><path class="zey5ebc0a"/><path class="l8unaacgj"/><path class="m2zfyio4u"/><path class="s91z9mxxg"/><path class="uqi2guhey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:breathe-in-duotone-bold" {...props}></Icon>
<style>
:global(.l8unaacgj) {
  d: path("M2 12h5");
}

:global(.m2zfyio4u) {
  d: path("m5 10 2 2 -2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s91z9mxxg) {
  d: path("M22 12h-5");
}

:global(.uqi2guhey) {
  d: path("m19 10 -2 2 2 2");
}

:global(.x6e_qy8ax) {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
