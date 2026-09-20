<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bp22adc3a"/><path class="jfgjrrsxx"/><path class="khupvdbel"/><path class="x7qdjyb5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-left-down-duotone-bold" {...props}></Icon>
<style>
:global(.bp22adc3a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4H10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jfgjrrsxx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.khupvdbel) {
  d: path("M20 4H10v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x7qdjyb5k) {
  d: path("m5 15 5 5 5 -5");
}

</style>
