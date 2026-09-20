<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_z-4bu9m"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="kcomyoe5y"/><path class="lhus_vb3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:locked-block-duotone-bold" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.kcomyoe5y) {
  d: path("M9 12h6v3H9Z");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.lhus_vb3v) {
  d: path("M10.5 12a1.5 1.5 0 0 1 3 0");
}

:global(.s_z-4bu9m) {
  fill: currentColor;
  d: path("M9 12h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
