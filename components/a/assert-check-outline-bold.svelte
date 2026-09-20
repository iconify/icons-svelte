<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pev_t0bpq"/><path class="vdp61xcuu"/><path class="ik6cgdc2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:assert-check-outline-bold" {...props}></Icon>
<style>
:global(.ik6cgdc2x) {
  d: path("m8.5 12 2.5 2.5 5 -5");
}

:global(.pev_t0bpq) {
  d: path("M7.5 4H5v16h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vdp61xcuu) {
  d: path("M16.5 4H19v16h-2.5");
}

</style>
