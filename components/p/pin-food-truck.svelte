<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yc24h2aja"/><path class="ekwka7byk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-food-truck" {...props}></Icon>
<style>
:global(.ekwka7byk) {
  d: path("M4.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 8h9v2a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yc24h2aja) {
  d: path("M2.5 4.5H16V16H2.5ZM16 8h2.75l2.75 3.5V16H16");
}

</style>
