<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="unzah8ysn"/><path class="qfcrftzhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:latency-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qfcrftzhy) {
  d: path("M4 3h16l-8 8 8 8H4l8 -8Z");
}

:global(.unzah8ysn) {
  fill: currentColor;
  d: path("M4 3h16l-8 8 8 8H4l8 -8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
