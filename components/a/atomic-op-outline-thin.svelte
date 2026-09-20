<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pev_t0bpq"/><path class="vdp61xcuu"/><path class="enrpg0aoq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:atomic-op-outline-thin" {...props}></Icon>
<style>
:global(.enrpg0aoq) {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pev_t0bpq) {
  d: path("M7.5 4H5v16h2.5");
}

:global(.vdp61xcuu) {
  d: path("M16.5 4H19v16h-2.5");
}

</style>
