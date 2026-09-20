<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mgc5w0bas"/><path class="nfsra8bqu"/><path class="nw8-8vb0d"/><path class="tt9689b6q"/><path class="gt7coxqxq"/><path class="gvmht2kii"/><path class="iedujiqkb"/><path class="rvtpkuisl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diffusion-duotone-bold" {...props}></Icon>
<style>
:global(.gt7coxqxq) {
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gvmht2kii) {
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mgc5w0bas) {
  fill: currentColor;
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nfsra8bqu) {
  fill: currentColor;
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nw8-8vb0d) {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rvtpkuisl) {
  d: path("M12 8a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tt9689b6q) {
  fill: currentColor;
  d: path("M12 8a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
