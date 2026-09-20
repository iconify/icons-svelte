<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cljv9cb7j"/><path class="jkh2r59sx"/><path class="qrhqs_vfa"/><path class="mi5wk5bvv"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="l7lvdwbxu"/><path class="jtt2bi6nu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:merchant-account-duotone-thin" {...props}></Icon>
<style>
:global(.cljv9cb7j) {
  fill: currentColor;
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkh2r59sx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jtt2bi6nu) {
  d: path("M8 18.5h8");
}

:global(.l7lvdwbxu) {
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mi5wk5bvv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 18.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrhqs_vfa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

</style>
