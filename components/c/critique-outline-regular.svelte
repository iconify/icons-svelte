<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="kpspt_bpo"/><path class="zf9agzw6m"/><path class="xfkhbxb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:critique-outline-regular" {...props}></Icon>
<style>
:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xfkhbxb0u) {
  d: path("M6 16 17 5");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

:global(.zf9agzw6m) {
  d: path("M7 13h7");
}

</style>
