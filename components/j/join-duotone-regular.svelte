<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hdls9bcen"/><path class="oro_30bhe"/><path class="x5-v1c34k"/><path class="r1giuh9in"/><path class="l517yxbln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:join-duotone-regular" {...props}></Icon>
<style>
:global(.hdls9bcen) {
  fill: currentColor;
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oro_30bhe) {
  fill: currentColor;
  d: path("M10 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r1giuh9in) {
  d: path("M10 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.x5-v1c34k) {
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

</style>
