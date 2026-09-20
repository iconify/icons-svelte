<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzxtpfb7v"/><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="nbil0n-ak"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="zohykibek"/><path class="kl5egs07h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:request-id-api-duotone-thin" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.eh---ab1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kl5egs07h) {
  d: path("M9.5 12.5 12 15l2.5 -2.5");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.nbil0n-ak) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 12.5 12 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tzxtpfb7v) {
  fill: currentColor;
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zohykibek) {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
