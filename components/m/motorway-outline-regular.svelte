<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="i2-ny_bzf"/><path class="vw_dl18nv"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motorway-outline-regular" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.lwdt7zb5f) {
  d: path("M4 2v20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pk1ekjvnl) {
  d: path("M20 2v20");
}

:global(.vw_dl18nv) {
  d: path("M12 10.5v3");
}

</style>
