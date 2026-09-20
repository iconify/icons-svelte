<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kbaghgqhh"/><path class="s_o_4bc7h"/><path class="v2np2ebwn"/><path class="zva0qcbrg"/><path class="xhii43btc"/><path class="wg9_q_bco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:clipboard-edit-duotone-regular" {...props}></Icon>
<style>
:global(.kbaghgqhh) {
  fill: currentColor;
  d: path("M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s_o_4bc7h) {
  fill: currentColor;
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v2np2ebwn) {
  fill: currentColor;
  d: path("M9 18v-2.5l4.5 -4.5 2.5 2.5 -4.5 4.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wg9_q_bco) {
  d: path("M9 18v-2.5l4.5 -4.5 2.5 2.5 -4.5 4.5Z");
}

:global(.xhii43btc) {
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.zva0qcbrg) {
  d: path("M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
