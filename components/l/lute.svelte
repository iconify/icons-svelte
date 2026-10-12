<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s--eem49q"/><circle class="dfom1ccsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lute" {...props}></Icon>
<style>
:global(.dfom1ccsl) {
  cx: 9px;
  cy: 13.5px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s--eem49q) {
  d: path("M4.4 18.1a6.5 5-45 1 0 9.2-9.2a6.5 5-45 1 0-9.2 9.2m9.2-9.2L18 4.5m0 0l3 3");
}

</style>
