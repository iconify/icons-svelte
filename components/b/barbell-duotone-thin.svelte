<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc0pq4b_o"/><path class="ydrfk9w6p"/><path class="lg9uabb_p"/><path class="txwhaib5d"/><path class="c8lxf1b3v"/><path class="vslz5yb3q"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gfdpeof0d"/><path class="y_uork5-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barbell-duotone-thin" {...props}></Icon>
<style>
:global(.c8lxf1b3v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cc0pq4b_o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gfdpeof0d) {
  d: path("M9 7v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lg9uabb_p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.tkeq0bpvv) {
  d: path("M18 4v16");
}

:global(.txwhaib5d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.y_uork5-p) {
  d: path("M15 7v10");
}

:global(.ydrfk9w6p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
