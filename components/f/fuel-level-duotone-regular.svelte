<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ixi7zdzcw"/><path class="lve95kzti"/><path class="vw_sh49yx"/><path class="c5wjx8n3c"/><path class="l2nbo7bgf"/><path class="m-p3hbclp"/><path class="exre5jj_d"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fuel-level-duotone-regular" {...props}></Icon>
<style>
:global(.c5wjx8n3c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.exre5jj_d) {
  d: path("m12 15 -4.5 -4.5");
}

:global(.ixi7zdzcw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.l2nbo7bgf) {
  d: path("M4 15a8 8 0 0 1 16 0");
}

:global(.lve95kzti) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vw_sh49yx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 15 -4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
