<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5ou-7bav"/><path class="i2-ny_bzf"/><path class="kpq1gpbkz"/><path class="z8g2jgblp"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:boxplot-duotone-thin" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.kpq1gpbkz) {
  d: path("M5 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.l5ou-7bav) {
  fill: currentColor;
  d: path("M5 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>
