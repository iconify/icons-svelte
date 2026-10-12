<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c0z4o9b5t"/><path class="g91r1v1en"/><circle class="lw-29wg_i"/><path class="qqw7ehgrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lease-contract" {...props}></Icon>
<style>
:global(.c0z4o9b5t) {
  d: path("M6 2.75h7.5l4.75 4.75V20A1.25 1.25 0 0 1 17 21.25H6A1.25 1.25 0 0 1 4.75 20V4A1.25 1.25 0 0 1 6 2.75");
}

:global(.g91r1v1en) {
  d: path("M13.5 2.75V7.5h4.75M7.75 7h3m-3 3h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lw-29wg_i) {
  cx: 12px;
  cy: 15.5px;
  r: 2.5px;
}

:global(.qqw7ehgrx) {
  d: path("M10.75 17.75v2.75l1.25-.85l1.25.85v-2.75");
}

</style>
