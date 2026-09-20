<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="po7z3iorz"/><path class="y3ufgvbmf"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e8t0a9beq"/><path class="zn6_kf4ff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coverage-branch-duotone-thin" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.e8t0a9beq) {
  d: path("M12 7v4l-4 4");
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

:global(.po7z3iorz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v4l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y3ufgvbmf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 11 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zn6_kf4ff) {
  d: path("m12 11 4 4");
}

</style>
