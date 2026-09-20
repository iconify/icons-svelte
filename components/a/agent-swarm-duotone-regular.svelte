<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znp-i32pq"/><path class="lwqfh8peb"/><path class="guh498h3i"/><path class="aybxv484y"/><path class="i8x8w8brl"/><path class="h7k_twb0c"/><path class="jt9_y_e3f"/><path class="d_0vbfv0w"/><path class="ad0-p6dru"/><path class="wylvx_bde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-swarm-duotone-regular" {...props}></Icon>
<style>
:global(.ad0-p6dru) {
  d: path("M12.27 10.28a3 3 0 1 1 -2.54 0");
}

:global(.aybxv484y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.27 10.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d_0vbfv0w) {
  d: path("M20.27 11.28a3 3 0 1 1 -2.54 0");
}

:global(.guh498h3i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20.27 11.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.i8x8w8brl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.27 16.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jt9_y_e3f) {
  d: path("M17.27 2.28a3 3 0 1 1 -2.54 0");
}

:global(.lwqfh8peb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.27 2.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wylvx_bde) {
  d: path("M8.27 16.28a3 3 0 1 1 -2.54 0");
}

:global(.znp-i32pq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
