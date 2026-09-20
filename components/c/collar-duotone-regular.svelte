<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pzx9fiuzq"/><path class="ixcwxesqy"/><path class="wqteuxb0p"/><path class="bo9_g-q3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collar-duotone-regular" {...props}></Icon>
<style>
:global(.bo9_g-q3m) {
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ixcwxesqy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzx9fiuzq) {
  fill: currentColor;
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wqteuxb0p) {
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
}

</style>
