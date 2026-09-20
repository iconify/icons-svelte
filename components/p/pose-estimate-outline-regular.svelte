<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq9ly31-r"/><path class="y2-meob4g"/><path class="zp4961b8b"/><path class="sc-u_pmnm"/><path class="hcbabq6mn"/><path class="mk6myd_hq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pose-estimate-outline-regular" {...props}></Icon>
<style>
:global(.hcbabq6mn) {
  d: path("m12 15 -5 5");
}

:global(.mk6myd_hq) {
  d: path("m12 15 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.sc-u_pmnm) {
  d: path("m17 14 -5 -5");
}

:global(.y2-meob4g) {
  d: path("M12 6v9");
}

:global(.zp4961b8b) {
  d: path("m7 14 5 -5");
}

</style>
