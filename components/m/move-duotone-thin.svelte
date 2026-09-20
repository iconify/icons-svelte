<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj8ybccjk"/><path class="j2r1pso3k"/><path class="r8-d-gbco"/><path class="g1gntlbfm"/><path class="myu_xsffd"/><path class="gv3gpab3b"/><path class="r7xk8o29f"/><path class="sxlwlmkmh"/><path class="t407nkbfi"/><path class="qrqk-5btd"/><path class="cu_n5qbwp"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:move-duotone-thin" {...props}></Icon>
<style>
:global(.cu_n5qbwp) {
  d: path("m7 9 -3 3 3 3");
}

:global(.g1gntlbfm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gv3gpab3b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2r1pso3k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.myu_xsffd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 9 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrqk-5btd) {
  d: path("m9 17 3 3 3 -3");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.r8-d-gbco) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.t407nkbfi) {
  d: path("m9 7 3 -3 3 3");
}

:global(.wj8ybccjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
