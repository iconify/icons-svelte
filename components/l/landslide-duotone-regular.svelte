<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_ob72hqs"/><path class="zamec3bwb"/><path class="wbhbh5bix"/><path class="kakiz1beo"/><path class="gonglubgb"/><path class="cjsg0ab2y"/><path class="n48oibb_x"/><path class="mf-afdped"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:landslide-duotone-regular" {...props}></Icon>
<style>
:global(.b_ob72hqs) {
  fill: currentColor;
  d: path("M10 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.gonglubgb) {
  d: path("m2 6 6 6h6l6 6");
}

:global(.kakiz1beo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mf-afdped) {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n48oibb_x) {
  d: path("M10 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wbhbh5bix) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 6 6 6h6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zamec3bwb) {
  fill: currentColor;
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
