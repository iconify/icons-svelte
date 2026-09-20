<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y36t9bcby"/><path class="qlvopac9f"/><path class="jj48i0bjg"/><path class="bemidvb1k"/><path class="crv4i00bu"/><path class="wy8w_b5cr"/><path class="yk3ngthye"/><path class="buky010ih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metric-point-duotone-regular" {...props}></Icon>
<style>
:global(.bemidvb1k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.buky010ih) {
  d: path("M13 14v4");
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.jj48i0bjg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlvopac9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy8w_b5cr) {
  d: path("M4 21h18");
}

:global(.y36t9bcby) {
  fill: currentColor;
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yk3ngthye) {
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
