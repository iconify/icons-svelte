<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="jb_v2ub8s"/><path class="lqj39lbjv"/><path class="gghaaub-j"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="vslz5yb3q"/><path class="cvahx_bgf"/><path class="ji1cfccfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-alive-duotone-bold" {...props}></Icon>
<style>
:global(.cvahx_bgf) {
  d: path("m9 9 3 -3 3 3");
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gghaaub-j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jb_v2ub8s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ji1cfccfb) {
  d: path("m9 15 3 3 3 -3");
}

:global(.lqj39lbjv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 9 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
