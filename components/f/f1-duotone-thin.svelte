<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n95mv7bdf"/><path class="pvt56ab3s"/><path class="sdgafkcgw"/><path class="tb325cy_s"/><path class="vw_dl18nv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:f1-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n95mv7bdf) {
  fill: currentColor;
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pvt56ab3s) {
  fill: currentColor;
  d: path("M10 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sdgafkcgw) {
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.tb325cy_s) {
  d: path("M10 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.vw_dl18nv) {
  d: path("M12 10.5v3");
}

</style>
