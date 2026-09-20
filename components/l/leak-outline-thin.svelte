<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqtixbwqo"/><path class="saqo5mbad"/><path class="mj3xlxbyp"/><path class="kgr7y94lw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leak-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kgr7y94lw) {
  d: path("m12 13 2.5 2.5a3 3 0 1 1 -5 0Z");
}

:global(.mj3xlxbyp) {
  d: path("M14 5v6");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.saqo5mbad) {
  d: path("M10 5v6");
}

</style>
