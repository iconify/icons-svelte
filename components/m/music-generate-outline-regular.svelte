<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="v4hdeje_n"/><path class="u8mhf344d"/><path class="ojw5_mmlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-generate-outline-regular" {...props}></Icon>
<style>
:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojw5_mmlr) {
  d: path("M12.5 6 15 8.5");
}

:global(.u8mhf344d) {
  d: path("M12.5 6v6");
}

:global(.v4hdeje_n) {
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
