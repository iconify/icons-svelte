<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ew8w8y77a"/><path clip-rule="evenodd" class="nyc5e84ew"/><path class="am3xewb6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clipboard-x-sharp-duotone" {...props}></Icon>
<style>
:global(.am3xewb6t) {
  d: path("M8.7071 11.7071L15.2929 18.2929M15.2929 11.7071L8.7071 18.2929");
}

:global(.ew8w8y77a) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.4477 3.4477 3 4 3Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nyc5e84ew) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1L17 1C17.5523 1 18 1.4477 18 2L18 7C18 7.5523 17.5523 8 17 8L7 8C6.4477 8 6 7.5523 6 7L6 2C6 1.4477 6.4477 1 7 1ZM8 3L8 6L16 6L16 3L8 3Z");
  stroke: none;
}

</style>
