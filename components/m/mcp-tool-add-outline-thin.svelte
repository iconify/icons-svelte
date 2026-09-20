<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6ppytj7e"/><path class="uormpdb9p"/><path class="oong2tffv"/><path class="yrwh_6bgk"/><path class="vwhzfj1kv"/><path class="wluwrgbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-tool-add-outline-thin" {...props}></Icon>
<style>
:global(.f6ppytj7e) {
  d: path("M12 10h3a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3v-3l3 -3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oong2tffv) {
  d: path("M12 5v5");
}

:global(.uormpdb9p) {
  d: path("M9 5v5");
}

:global(.vwhzfj1kv) {
  d: path("M12 11.5v6");
}

:global(.wluwrgbwr) {
  d: path("M9 14.5h6");
}

:global(.yrwh_6bgk) {
  d: path("M15 5v5");
}

</style>
