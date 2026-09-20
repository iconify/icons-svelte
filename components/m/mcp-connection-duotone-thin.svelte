<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxrob3sge"/><path class="cpc3z_b1u"/><path class="qs5fm1nai"/><path class="nmybz-bqz"/><path class="dfcdzc65k"/><path class="yg66nzbgg"/><path class="avkaqpora"/><path class="kdmnrabtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-connection-duotone-thin" {...props}></Icon>
<style>
:global(.avkaqpora) {
  d: path("m13.5 13.5 2 2");
}

:global(.cpc3z_b1u) {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dfcdzc65k) {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdmnrabtq) {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nmybz-bqz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13.5 13.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qs5fm1nai) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8.5 8.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yg66nzbgg) {
  d: path("m8.5 8.5 2 2");
}

:global(.zxrob3sge) {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
