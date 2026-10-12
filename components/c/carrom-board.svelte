<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hgsfuxwte"/><path class="firku7bll"/><path class="ivnye2b_d"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:carrom-board" {...props}></Icon>
<style>
:global(.firku7bll) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 6.25h.01m11.49 0h.01M6.25 17.75h.01m11.49 0h.01");
}

:global(.hgsfuxwte) {
  width: 18px;
  height: 18px;
  x: 3px;
  y: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.ivnye2b_d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m.5 5.75h6M9 6.25h6");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
