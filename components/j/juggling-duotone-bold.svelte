<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lzzpbebvm"/><path class="pr270rb6e"/><path class="hf_zxrbcx"/><path class="l3lvvq3ob"/><path class="hrm50umfz"/><path class="d_xtg74gy"/><path class="mor-ojbak"/><path class="gcpl_duni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:juggling-duotone-bold" {...props}></Icon>
<style>
:global(.d_xtg74gy) {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gcpl_duni) {
  d: path("M12 4c6 1 8 7 4 11");
}

:global(.hf_zxrbcx) {
  fill: currentColor;
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hrm50umfz) {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l3lvvq3ob) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4c6 1 8 7 4 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lzzpbebvm) {
  fill: currentColor;
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mor-ojbak) {
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pr270rb6e) {
  fill: currentColor;
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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
