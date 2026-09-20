<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k628-abaf"/><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="hd5x_f8cb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pay-per-use-duotone-regular" {...props}></Icon>
<style>
:global(.hd5x_f8cb) {
  d: path("m21 7 -4 4h3l-4 4");
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

:global(.lh7nxd5dq) {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
