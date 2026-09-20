<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fm-6bpbzd"/><path class="s-u1j5bti"/><path class="k7npzjf1o"/><path class="sl2z8ub9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pollution-outline-thin" {...props}></Icon>
<style>
:global(.fm-6bpbzd) {
  d: path("M5 21v-9h5v9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7npzjf1o) {
  d: path("M7.5 12a3 3 0 0 1 0 -6");
}

:global(.s-u1j5bti) {
  d: path("M14 21v-6h5v6Z");
}

:global(.sl2z8ub9q) {
  d: path("M7.5 2a3 3 0 0 1 0 6");
}

</style>
