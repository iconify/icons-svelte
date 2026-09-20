<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yuvmmqrdc"/><path class="e0iy82b2q"/><path class="zy07-3bit"/><path class="za8zkd6ab"/><path class="oidvfgqrv"/><path class="i3ypschyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:past-paper-duotone-regular" {...props}></Icon>
<style>
:global(.e0iy82b2q) {
  d: path("M2 4a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.i3ypschyz) {
  d: path("M5 15h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oidvfgqrv) {
  d: path("M5 11h9");
}

:global(.yuvmmqrdc) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.za8zkd6ab) {
  d: path("M5 7h9");
}

:global(.zy07-3bit) {
  d: path("M6 21h15V6");
}

</style>
