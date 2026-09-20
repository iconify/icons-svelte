<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v4qx2ccfm"/><path class="sge-6ebfv"/><path class="rr985ibot"/><path class="c3a-odz8a"/><path class="akf7y5bsb"/><path class="xgyiae7-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-center-vertical-duotone-thin" {...props}></Icon>
<style>
:global(.akf7y5bsb) {
  d: path("M8 7h8v4H8Z");
}

:global(.c3a-odz8a) {
  d: path("M12 18.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rr985ibot) {
  d: path("M12 3v2.5");
}

:global(.sge-6ebfv) {
  fill: currentColor;
  d: path("M9.5 14h5v4h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v4qx2ccfm) {
  fill: currentColor;
  d: path("M8 7h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xgyiae7-j) {
  d: path("M9.5 14h5v4h-5Z");
}

</style>
