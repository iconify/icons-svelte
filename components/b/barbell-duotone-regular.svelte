<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bk5n09bgv"/><path class="cd3ob020j"/><path class="zhgf1vz5u"/><path class="cmp--hbhb"/><path class="l5ieewe3y"/><path class="vslz5yb3q"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gfdpeof0d"/><path class="y_uork5-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barbell-duotone-regular" {...props}></Icon>
<style>
:global(.bk5n09bgv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cd3ob020j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cmp--hbhb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gfdpeof0d) {
  d: path("M9 7v10");
}

:global(.l5ieewe3y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.zhgf1vz5u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
