<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vn749yfck"/><path class="qkrt1qbaa"/><path class="no2cffbmc"/><path class="iqekvccuu"/><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="hpd-e505b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-load-duotone-regular" {...props}></Icon>
<style>
:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.hpd-e505b) {
  d: path("M16.5 15.5 19 13l2.5 2.5");
}

:global(.iqekvccuu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 15.5 19 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ni-_lk7vs) {
  d: path("M5 5h10v6H5");
}

:global(.no2cffbmc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojq3d2bwe) {
  d: path("M5 3v18");
}

:global(.qkrt1qbaa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 5h10v6H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vn749yfck) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
