<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zstw_8bqr"/><path class="h-upazbnx"/><path class="g2hfxvq5b"/><path class="rp5jumb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moving-box-outline-regular" {...props}></Icon>
<style>
:global(.g2hfxvq5b) {
  d: path("m20 8 -3 -3");
}

:global(.h-upazbnx) {
  d: path("m4 8 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rp5jumb9f) {
  d: path("M12 8v11");
}

:global(.zstw_8bqr) {
  d: path("M4 8v11h16V8");
}

</style>
