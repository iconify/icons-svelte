<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="sk9etkb4u"/><path class="bn16a-b9r"/><path class="ln--q6bsf"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="kow2ilbqy"/><path class="zos4srk3e"/><path class="y40ry_bij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flag-rollout-duotone-bold" {...props}></Icon>
<style>
:global(.bn16a-b9r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.kow2ilbqy) {
  d: path("M8 10v3");
}

:global(.ln--q6bsf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 6v7");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.sk9etkb4u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y40ry_bij) {
  d: path("M14 6v7");
}

:global(.zos4srk3e) {
  d: path("M11 8v5");
}

:global(.zwjzc3g_l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
