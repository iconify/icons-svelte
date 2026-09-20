<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="s__6mz7kc"/><path class="ypekw-bou"/><path class="gell8hgqh"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="lip701r7h"/><path class="kikp0-sku"/><path class="jsj5j3bdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ndcg-duotone-thin" {...props}></Icon>
<style>
:global(.dba5rjonf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.gell8hgqh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 10.5V13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jsj5j3bdw) {
  d: path("M13 10.5V13");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.kikp0-sku) {
  d: path("M10 9v4");
}

:global(.lip701r7h) {
  d: path("M7 7v6");
}

:global(.s__6mz7kc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ypekw-bou) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 9v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zl5hlnbpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
