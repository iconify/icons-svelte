<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hrm50umfz"/><path class="d_xtg74gy"/><path class="mor-ojbak"/><path class="gcpl_duni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:juggling-outline-bold" {...props}></Icon>
<style>
:global(.d_xtg74gy) {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gcpl_duni) {
  d: path("M12 4c6 1 8 7 4 11");
}

:global(.hrm50umfz) {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mor-ojbak) {
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
