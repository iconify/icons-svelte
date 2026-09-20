<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qreoni42r"/><path class="pvea0fb0q"/><path class="sefvh1b3z"/><path class="xnxyw5beg"/><path class="zstw_8bqr"/><path class="h-upazbnx"/><path class="g2hfxvq5b"/><path class="rp5jumb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moving-box-duotone-thin" {...props}></Icon>
<style>
:global(.g2hfxvq5b) {
  d: path("m20 8 -3 -3");
}

:global(.h-upazbnx) {
  d: path("m4 8 3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pvea0fb0q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 8 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qreoni42r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v11h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rp5jumb9f) {
  d: path("M12 8v11");
}

:global(.sefvh1b3z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 8 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xnxyw5beg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zstw_8bqr) {
  d: path("M4 8v11h16V8");
}

</style>
