<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jg3ka1bkp"/><path class="nn22zo4jl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eggs-carton" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jg3ka1bkp) {
  d: path("M12 2.75c-4 0-7 6.25-7 11a7 7 0 0 0 14 0c0-4.75-3-11-7-11");
}

:global(.nn22zo4jl) {
  d: path("M8.5 14c0-1.75.5-3.5 1.5-5");
}

</style>
