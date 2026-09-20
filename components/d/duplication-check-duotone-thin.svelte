<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="mq3gpvbkh"/><path class="gihj4qbne"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jn24arf4i"/><path class="w8g3vrtdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:duplication-check-duotone-thin" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.eh---ab1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gihj4qbne) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jn24arf4i) {
  d: path("M8 10h6");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.mq3gpvbkh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w8g3vrtdm) {
  d: path("M10 14h6");
}

</style>
