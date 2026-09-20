<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="tm6fddb_n"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="pnyf9bzfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idle-block-duotone-thin" {...props}></Icon>
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

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.pnyf9bzfu) {
  d: path("M9 9h6l-6 6h6");
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tm6fddb_n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9h6l-6 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
