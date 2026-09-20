<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="viv5gg8xx"/><path class="rw6ho_bav"/><path class="ils7yp4cg"/><path class="pa38cub_q"/><path class="a3hpkcc6o"/><path class="ls7ugdcwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rack-outline-regular" {...props}></Icon>
<style>
:global(.a3hpkcc6o) {
  d: path("M6 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.ls7ugdcwr) {
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pa38cub_q) {
  d: path("M6 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.viv5gg8xx) {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
