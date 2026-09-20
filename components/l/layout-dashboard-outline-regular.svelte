<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n48w5yb-p"/><path class="r7xk8o29f"/><path class="em661fb9y"/><path class="gu38o4b7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:layout-dashboard-outline-regular" {...props}></Icon>
<style>
:global(.em661fb9y) {
  d: path("M2 10h10");
}

:global(.gu38o4b7d) {
  d: path("M12 14h10");
}

:global(.n48w5yb-p) {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

</style>
