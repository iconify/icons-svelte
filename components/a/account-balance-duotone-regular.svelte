<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dj4rgmtcm"/><path class="mcubrkb2y"/><path class="d27-dpb3f"/><path class="bx3fv3b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:account-balance-duotone-regular" {...props}></Icon>
<style>
:global(.bx3fv3b8c) {
  d: path("M12 13v4");
}

:global(.d27-dpb3f) {
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.dj4rgmtcm) {
  fill: currentColor;
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
