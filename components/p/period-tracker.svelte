<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwt28iams"/><path class="j935he2op"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:period-tracker" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j935he2op) {
  d: path("M12.5 8.25c1.6 2.1 3 3.6 3 5.25a3 3 0 0 1-6 0c0-1.65 1.4-3.15 3-5.25");
}

:global(.pwt28iams) {
  d: path("M17.98 7.02a7.75 7.75 0 1 1-5.48-2.27M10.75 3l1.75 1.75l-1.75 1.75");
}

</style>
