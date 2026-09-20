<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="astk27h5f"/><path class="fvjj8un4l"/><path class="lve95kzti"/><path class="wsqtwnb_f"/><path class="jof7c9fpk"/><path class="a6o5bdc8o"/><path class="m-p3hbclp"/><path class="z8bw_gbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-right-left-duotone-regular" {...props}></Icon>
<style>
:global(.a6o5bdc8o) {
  d: path("m16 5 4 4 -4 4");
}

:global(.astk27h5f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fvjj8un4l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 5 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
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

:global(.wsqtwnb_f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 11 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z8bw_gbrq) {
  d: path("m8 11 -4 4 4 4");
}

</style>
