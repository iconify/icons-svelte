<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="d3yh5cbqf"/><path class="ub-9albao"/><rect class="abdx7zvuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:masala-dabba" {...props}></Icon>
<style>
:global(.abdx7zvuq) {
  width: 16px;
  height: 10px;
  x: 4px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.d3yh5cbqf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4.5h.01");
}

:global(.ub-9albao) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
