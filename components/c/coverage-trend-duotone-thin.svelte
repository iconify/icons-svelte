<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="juvl5cc7r"/><path class="f87iv5b9i"/><path class="xl3k3gb4y"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="fs--blxyx"/><path class="xxenxccpt"/><path class="hlt9oudyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coverage-trend-duotone-thin" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.eh---ab1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f87iv5b9i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fs--blxyx) {
  d: path("M9 13v3");
}

:global(.hlt9oudyd) {
  d: path("M15 9v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.juvl5cc7r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xl3k3gb4y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xxenxccpt) {
  d: path("M12 11v5");
}

</style>
