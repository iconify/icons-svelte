<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="pk0ihtiow"/><path class="mw-9m66dl"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="kn8ghfb-y"/><path class="s-gg8lbxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:click-and-collect-duotone-bold" {...props}></Icon>
<style>
:global(.fmbgtccaf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn8ghfb-y) {
  d: path("M12 11v6.5");
}

:global(.mw-9m66dl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 15 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pk0ihtiow) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s-gg8lbxh) {
  d: path("m9.5 15 2.5 2.5 2.5 -2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

:global(.z6qs6gbnt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
