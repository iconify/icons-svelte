<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="vtd1qpbly"/><path class="dpzjt7pku"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="icvc39peu"/><path class="xios20bld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milestone-filter-duotone-bold" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.dpzjt7pku) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.icvc39peu) {
  d: path("m9 7 3 3 3 -3");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.qn-h03e3f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vtd1qpbly) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 7 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xios20bld) {
  d: path("M12 10v3");
}

:global(.zwjzc3g_l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
