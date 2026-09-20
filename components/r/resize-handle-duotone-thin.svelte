<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="encdkxb_m"/><path class="g_uiugb1x"/><path class="jx94tacen"/><path class="htx64eiti"/><path class="j0xsopbwy"/><path class="dq5olwsrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:resize-handle-duotone-thin" {...props}></Icon>
<style>
:global(.dq5olwsrs) {
  d: path("m21.5 18.5 -3 3");
}

:global(.encdkxb_m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 5.5 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g_uiugb1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 12.5 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htx64eiti) {
  d: path("m21.5 5.5 -16 16");
}

:global(.j0xsopbwy) {
  d: path("m21.5 12.5 -9 9");
}

:global(.jx94tacen) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 18.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
