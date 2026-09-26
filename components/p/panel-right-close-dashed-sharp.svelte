<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xsa8rjksl"/><path class="q_i5o_bfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-close-dashed-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q_i5o_bfs) {
  d: path("M7.7071 8.7071L11 12L7.7071 15.2929");
}

:global(.xsa8rjksl) {
  d: path("M15 3L21 3L21 21L15 21L15 3ZM7 3L3 3L3 7M3 17L3 21L7 21M9 3L12 3M9 21L12 21M3 9.5L3 14.5");
}

</style>
