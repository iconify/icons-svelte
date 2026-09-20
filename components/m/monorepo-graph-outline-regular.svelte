<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jrpnc2pnl"/><path class="swzjdoakn"/><path class="gp6zu7b7w"/><path class="vcu2yzb_j"/><path class="c8tpvpbrt"/><path class="a5a5iacnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:monorepo-graph-outline-regular" {...props}></Icon>
<style>
:global(.a5a5iacnl) {
  d: path("M15 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.c8tpvpbrt) {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gp6zu7b7w) {
  d: path("m11 10 -2.5 2.5");
}

:global(.jrpnc2pnl) {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.swzjdoakn) {
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vcu2yzb_j) {
  d: path("m13 10 2.5 2.5");
}

</style>
