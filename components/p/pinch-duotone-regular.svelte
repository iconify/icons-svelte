<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xex4mubwu"/><path class="fkwggwbnq"/><path class="jyaut3m_p"/><path class="v99oh6bph"/><path class="fpxzcl19b"/><path class="m3uk2nwvd"/><path class="v8mti3bcl"/><path class="m_x-fjbot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pinch-duotone-regular" {...props}></Icon>
<style>
:global(.fkwggwbnq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5.5V9H5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fpxzcl19b) {
  d: path("m3 3 6 6");
}

:global(.jyaut3m_p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 21 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_x-fjbot) {
  d: path("M15 18.5V15h3.5");
}

:global(.m3uk2nwvd) {
  d: path("M9 5.5V9H5.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v8mti3bcl) {
  d: path("m21 21 -6 -6");
}

:global(.v99oh6bph) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 18.5V15h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xex4mubwu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 3 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
