<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bk5n09bgv"/><path class="hraf8u3ac"/><path class="uuob7-_wx"/><path class="zjfasgbxn"/><path class="nngli2bzi"/><path class="vslz5yb3q"/><path class="xhm9ckc2y"/><path class="gl0vd86ea"/><path class="h26bvabki"/><path class="tmc4aacim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dumbbell-duotone-regular" {...props}></Icon>
<style>
:global(.bk5n09bgv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gl0vd86ea) {
  d: path("M18 7v10");
}

:global(.h26bvabki) {
  d: path("M3 9v6");
}

:global(.hraf8u3ac) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nngli2bzi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tmc4aacim) {
  d: path("M21 9v6");
}

:global(.uuob7-_wx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.xhm9ckc2y) {
  d: path("M6 7v10");
}

:global(.zjfasgbxn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
