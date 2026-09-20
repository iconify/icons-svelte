<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwmow_bne"/><path class="a9034eb-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hydro-power-outline-thin" {...props}></Icon>
<style>
:global(.a9034eb-p) {
  d: path("m14 8 -5 5h3l-4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwmow_bne) {
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
}

</style>
