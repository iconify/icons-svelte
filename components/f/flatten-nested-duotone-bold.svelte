<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_o_4bc7h"/><path class="xhii43btc"/><path class="icp673bbo"/><path class="ko0o6vb7i"/><path class="s4l_k6b-t"/><path class="nuugr4b2c"/><path class="e1kd5d-qm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flatten-nested-duotone-bold" {...props}></Icon>
<style>
:global(.e1kd5d-qm) {
  d: path("M17 20h4");
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.ko0o6vb7i) {
  d: path("M5 16v-4h14v4");
}

:global(.nuugr4b2c) {
  d: path("M10 20h4");
}

:global(.s_o_4bc7h) {
  fill: currentColor;
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
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

:global(.s4l_k6b-t) {
  d: path("M3 20h4");
}

:global(.xhii43btc) {
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
