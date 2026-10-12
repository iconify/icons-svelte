<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vfac8le9e"/><path class="q65xz8b1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:e-waste" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q65xz8b1w) {
  d: path("m12.75 10.25l-2.5 4.25h3.5l-2.5 4");
}

:global(.vfac8le9e) {
  d: path("M6.5 7.75h11q1.5 0 1.36 1.49l-.97 10.52q-.14 1.49-1.64 1.49h-8.5q-1.5 0-1.64-1.49L5.14 9.24Q5 7.75 6.5 7.75m-3.25-2.5h17.5m-11 0v-2.5h4.5v2.5");
}

</style>
