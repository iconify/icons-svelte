<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="om5ur5t0p"/><path class="l6cp2-b8s"/><path class="x9kn15bcl"/><path class="a7vpafiwa"/><path class="msaz94ywr"/><path class="fmjpvzbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:release-tag-duotone-bold" {...props}></Icon>
<style>
:global(.a7vpafiwa) {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fmjpvzbts) {
  d: path("M11 14h5");
}

:global(.l6cp2-b8s) {
  fill: currentColor;
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.msaz94ywr) {
  d: path("M11 10h7");
}

:global(.om5ur5t0p) {
  fill: currentColor;
  d: path("m2 12 7 -7h12v14H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x9kn15bcl) {
  d: path("m2 12 7 -7h12v14H9Z");
}

</style>
