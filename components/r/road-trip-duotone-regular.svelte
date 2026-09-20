<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n353dnb7w"/><path class="swjmh6vfi"/><path class="v6ic8acqd"/><path class="e4zwoub_y"/><path class="t1w08ccuz"/><path class="g7ipnac6i"/><path class="icp673bbo"/><path class="pa9quik2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:road-trip-duotone-regular" {...props}></Icon>
<style>
:global(.e4zwoub_y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 16v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g7ipnac6i) {
  d: path("m21 20 -6 -6V5");
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.n353dnb7w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 20 6 -6V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pa9quik2g) {
  d: path("M12 16v3");
}

:global(.swjmh6vfi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 20 -6 -6V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1w08ccuz) {
  d: path("m3 20 6 -6V5");
}

:global(.v6ic8acqd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
