<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ya3ccj28z"/><path class="ucd51obdt"/><path class="j2f7om_-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cool-down-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2f7om_-b) {
  d: path("m16 15 3 3 3 -3");
}

:global(.ucd51obdt) {
  d: path("M19 6v12");
}

:global(.ya3ccj28z) {
  d: path("m8 4 4 4a5.5 5.5 0 1 1 -8 0Z");
}

</style>
