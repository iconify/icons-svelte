<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mn41dg4yb"/><rect class="xufr8n3ha"/><path class="lf_mttb8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:remote-work" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lf_mttb8i) {
  d: path("M8.25 18.25h7.5");
}

:global(.mn41dg4yb) {
  d: path("M5.25 9.5L12 3.75l6.75 5.75v9.75a2 2 0 0 1-2 2h-9.5a2 2 0 0 1-2-2Z");
}

:global(.xufr8n3ha) {
  width: 6px;
  height: 4.25px;
  x: 9px;
  y: 11px;
  rx: 1px;
}

</style>
