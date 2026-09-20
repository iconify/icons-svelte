<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vslz5yb3q"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gfdpeof0d"/><path class="y_uork5-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barbell-outline-regular" {...props}></Icon>
<style>
:global(.gfdpeof0d) {
  d: path("M9 7v10");
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkeq0bpvv) {
  d: path("M18 4v16");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.y_uork5-p) {
  d: path("M15 7v10");
}

</style>
