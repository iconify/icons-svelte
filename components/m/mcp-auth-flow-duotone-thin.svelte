<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exn420ato"/><path class="pfsnloz0n"/><path class="jyx9rotkq"/><path class="ni20md-jo"/><path class="j6o0shbiv"/><path class="uesvxd39h"/><path class="sdxgilt-v"/><path class="hywm61bgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-auth-flow-duotone-thin" {...props}></Icon>
<style>
:global(.exn420ato) {
  fill: currentColor;
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hywm61bgw) {
  d: path("M10.5 11a1.5 1.5 0 0 1 3 0");
}

:global(.j6o0shbiv) {
  d: path("M7 18h5");
}

:global(.jyx9rotkq) {
  fill: currentColor;
  d: path("M9 11h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ni20md-jo) {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
}

:global(.pfsnloz0n) {
  fill: currentColor;
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sdxgilt-v) {
  d: path("M9 11h6v3H9Z");
}

:global(.uesvxd39h) {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
