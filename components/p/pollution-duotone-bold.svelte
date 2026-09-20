<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="etl76_28z"/><path class="t5oi8bw4w"/><path class="fm-6bpbzd"/><path class="s-u1j5bti"/><path class="k7npzjf1o"/><path class="sl2z8ub9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pollution-duotone-bold" {...props}></Icon>
<style>
:global(.etl76_28z) {
  fill: currentColor;
  d: path("M5 21v-9h5v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fm-6bpbzd) {
  d: path("M5 21v-9h5v9Z");
}

:global(.k7npzjf1o) {
  d: path("M7.5 12a3 3 0 0 1 0 -6");
}

:global(.s-u1j5bti) {
  d: path("M14 21v-6h5v6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sl2z8ub9q) {
  d: path("M7.5 2a3 3 0 0 1 0 6");
}

:global(.t5oi8bw4w) {
  fill: currentColor;
  d: path("M14 21v-6h5v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
