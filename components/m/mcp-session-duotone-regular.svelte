<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mpmvm0b2b"/><path class="b4bbhnb2u"/><path class="tlav9kbbk"/><path class="xios20bld"/><path class="m2e5l4bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-session-duotone-regular" {...props}></Icon>
<style>
:global(.b4bbhnb2u) {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7l3 -3h4");
}

:global(.m2e5l4bvn) {
  d: path("M13 13h3");
}

:global(.mpmvm0b2b) {
  fill: currentColor;
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7l3 -3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tlav9kbbk) {
  d: path("M13.69 9.37a4 4 0 1 1 -3.38 0");
}

:global(.xios20bld) {
  d: path("M12 10v3");
}

</style>
