<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="q1m15dbht"/><path class="yb2rg_4rf"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:roulette-wheel-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.q1m15dbht) {
  cx: 12px;
  cy: 12px;
  r: 5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yb2rg_4rf) {
  d: path("M17 12h4.25M7 12H2.75M12 7V2.75M12 17v4.25m3.54-5.71l3 3M8.46 8.46l-3-3m10.08 3l3-3M8.46 15.54l-3 3");
}

</style>
