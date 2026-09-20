<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p4o40ib9j"/><path class="zi-05bc7q"/><path class="jl3jsq9eu"/><path class="bmfr0nb4l"/><path class="g6bypobmt"/><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="i2-ny_bzf"/><path class="vw_dl18nv"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motorway-duotone-bold" {...props}></Icon>
<style>
:global(.bmfr0nb4l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.g6bypobmt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.jl3jsq9eu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lwdt7zb5f) {
  d: path("M4 2v20");
}

:global(.p4o40ib9j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pk1ekjvnl) {
  d: path("M20 2v20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vw_dl18nv) {
  d: path("M12 10.5v3");
}

:global(.zi-05bc7q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
