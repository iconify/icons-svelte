<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m7ezp3bui"/><path class="ls7ugdcwr"/><path class="if5ft31dv"/><path class="ki3b7s-pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cost-cloud-outline-regular" {...props}></Icon>
<style>
:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ki3b7s-pe) {
  d: path("M16 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ls7ugdcwr) {
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m7ezp3bui) {
  d: path("M4 15a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 6a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
