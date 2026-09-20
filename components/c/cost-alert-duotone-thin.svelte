<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k628-abaf"/><path class="qaekcdczc"/><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="g0zr_zwdg"/><path class="ktzvm-xej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cost-alert-duotone-thin" {...props}></Icon>
<style>
:global(.g0zr_zwdg) {
  d: path("M18 6v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ji-xh3b0v) {
  d: path("M8 10.5v3");
}

:global(.k628-abaf) {
  fill: currentColor;
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ktzvm-xej) {
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lh7nxd5dq) {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.qaekcdczc) {
  fill: currentColor;
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
