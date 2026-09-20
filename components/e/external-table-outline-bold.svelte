<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uuszqcc8s"/><path class="r1kul9sai"/><path class="x_i4bic-b"/><path class="s6pz8xbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:external-table-outline-bold" {...props}></Icon>
<style>
:global(.r1kul9sai) {
  d: path("M2 11h13");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6pz8xbpf) {
  d: path("m15 10 6 -6");
}

:global(.uuszqcc8s) {
  d: path("M2 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.x_i4bic-b) {
  d: path("m17 8 4 -4v5");
}

</style>
