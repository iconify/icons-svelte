<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="or_6s743l"/><path class="jkb466bme"/><path class="p7np2t4-r"/><path class="kk-ohg6gv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crop-duotone-bold" {...props}></Icon>
<style>
:global(.jkb466bme) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h16v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kk-ohg6gv) {
  d: path("M2 6h16v16");
}

:global(.or_6s743l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 2v16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p7np2t4-r) {
  d: path("M6 2v16h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
