<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8c8atiya"/><path class="n0n63pb2v"/><path class="duu12rf5n"/><path class="wqcl8_ygf"/><path class="xxf06_b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-index-duotone-thin" {...props}></Icon>
<style>
:global(.duu12rf5n) {
  d: path("M10 5.5v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m8c8atiya) {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.wqcl8_ygf) {
  d: path("M14 5.5v6");
}

:global(.xxf06_b4i) {
  d: path("M8 8.5h8");
}

</style>
