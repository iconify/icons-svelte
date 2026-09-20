<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og62tq4bb"/><path class="rzbw9hbaj"/><path class="qaw_x5ree"/><path class="hl-uapbht"/><path class="p5dc1z72h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:on-call-duotone-thin" {...props}></Icon>
<style>
:global(.hl-uapbht) {
  d: path("M15 5a3 3 0 0 1 0 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.og62tq4bb) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p5dc1z72h) {
  d: path("M15 2a6 6 0 0 1 0 12");
}

:global(.qaw_x5ree) {
  d: path("M5 17h4");
}

:global(.rzbw9hbaj) {
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
