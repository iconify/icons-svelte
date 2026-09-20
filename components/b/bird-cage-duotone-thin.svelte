<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5k5h0b_y"/><path class="xrewtmnla"/><path class="uaizx0bey"/><path class="d_ske9b8y"/><path class="zkgvk4bog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bird-cage-duotone-thin" {...props}></Icon>
<style>
:global(.d_ske9b8y) {
  d: path("M15 7v13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t5k5h0b_y) {
  fill: currentColor;
  d: path("M5 20v-8c0 -4 3 -7 7 -7s7 3 7 7v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uaizx0bey) {
  d: path("M9 7v13");
}

:global(.xrewtmnla) {
  d: path("M5 20v-8c0 -4 3 -7 7 -7s7 3 7 7v8Z");
}

:global(.zkgvk4bog) {
  d: path("M12 2v3");
}

</style>
