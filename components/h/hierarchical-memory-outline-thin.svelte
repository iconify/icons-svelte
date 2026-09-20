<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="meb7wcbot"/><path class="o40l0bbgl"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hierarchical-memory-outline-thin" {...props}></Icon>
<style>
:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.meb7wcbot) {
  d: path("M7 5h10");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.o40l0bbgl) {
  d: path("M9 8.5h6");
}

</style>
