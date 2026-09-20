<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="f9z-0cczq"/><path class="vmk3-8b7s"/><path class="wluwrgbwr"/><path class="xaqt94wpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:document-config-outline-regular" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.f9z-0cczq) {
  d: path("M9 10.5h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vmk3-8b7s) {
  d: path("M13.5 8.5v4");
}

:global(.wluwrgbwr) {
  d: path("M9 14.5h6");
}

:global(.xaqt94wpa) {
  d: path("M10.5 12.5v4");
}

</style>
