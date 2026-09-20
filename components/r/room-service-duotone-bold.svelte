<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="grt7vrw-d"/><path class="t9q8gebqk"/><path class="m_-sm9bqc"/><path class="obdvbgbhd"/><path class="ils7yp4cg"/><path class="bv1y61bvs"/><path class="us2evabuy"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:room-service-duotone-bold" {...props}></Icon>
<style>
:global(.bv1y61bvs) {
  d: path("M4 16a8 8 0 0 1 16 0");
}

:global(.grt7vrw-d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.m_-sm9bqc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.obdvbgbhd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t9q8gebqk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.us2evabuy) {
  d: path("M12 5.5V8");
}

</style>
