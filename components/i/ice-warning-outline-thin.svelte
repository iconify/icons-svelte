<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uweslxo3x"/><path class="o5dmv_b0u"/><path class="j7s0b5bvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ice-warning-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7s0b5bvf) {
  d: path("M15 13.5v5m-2.5 0 5 -5");
}

:global(.o5dmv_b0u) {
  d: path("M9 11.5v5m-2.5 0 5 -5");
}

:global(.uweslxo3x) {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>
