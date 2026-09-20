<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxow7abeb"/><path class="abnm6smsv"/><path class="y-192i3fd"/><path class="kd8pirhpr"/><path class="uw80e4dke"/><path class="i7v-iobnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:content-negotiation-duotone-thin" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7v-iobnd) {
  d: path("M11.5 12.5 9 15l2.5 2.5");
}

:global(.kd8pirhpr) {
  d: path("M12.5 6.5 15 9l-2.5 2.5");
}

:global(.uw80e4dke) {
  d: path("M11 15h5");
}

:global(.y-192i3fd) {
  d: path("M8 9h5");
}

:global(.yxow7abeb) {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
