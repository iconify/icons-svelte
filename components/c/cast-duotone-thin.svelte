<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6zj4iekt"/><path class="kburqr_hv"/><path class="pty_wsbvs"/><path class="gcalxb98a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cast-duotone-thin" {...props}></Icon>
<style>
:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kburqr_hv) {
  d: path("M8 4h8v13h4v4H8Z");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.q6zj4iekt) {
  fill: currentColor;
  d: path("M8 4h8v13h4v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
