<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rbzpndy-d"/><path class="gd8l1w4ql"/><path class="d4v3t3bns"/><path class="oboujbbaa"/><path class="rdidnh2az"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:canonicalize-duotone-bold" {...props}></Icon>
<style>
:global(.d4v3t3bns) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gd8l1w4ql) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oboujbbaa) {
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.rbzpndy-d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdidnh2az) {
  d: path("m10 11.5 2 2 2 -2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
