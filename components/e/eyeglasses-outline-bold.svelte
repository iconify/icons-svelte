<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zwwtt2bhd"/><path class="iopx9qkhf"/><path class="khp0b8bxr"/><path class="ou2rz6bri"/><path class="vo_28p0qr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:eyeglasses-outline-bold" {...props}></Icon>
<style>
:global(.iopx9qkhf) {
  d: path("M13 13a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.khp0b8bxr) {
  d: path("M10.5 13h3");
}

:global(.ou2rz6bri) {
  d: path("m2 9 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vo_28p0qr) {
  d: path("m22 9 -2 2");
}

:global(.zwwtt2bhd) {
  d: path("M2 13a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

</style>
