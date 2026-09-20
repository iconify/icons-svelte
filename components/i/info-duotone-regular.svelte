<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhy5nnbig"/><path class="w2535ybvu"/><path class="o_ssmh9ez"/><path class="hv3ppsbji"/><path class="acx2mjbnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:info-duotone-regular" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.hv3ppsbji) {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.w2535ybvu) {
  fill: currentColor;
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zhy5nnbig) {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
