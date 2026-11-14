<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqhj_ra7i"/><path class="n6ee8vyxw"/><path class="zlio2ybos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:film-black-white" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mqhj_ra7i) {
  d: path("M2.5 4.5h19m-19 15h19M4.25 8h1A1.75 1.75 0 0 1 7 9.75v4.5A1.75 1.75 0 0 1 5.25 16h-1a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 4.25 8");
}

:global(.n6ee8vyxw) {
  fill: currentColor;
  d: path("M11.5 8h1a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 12.5 16h-1a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 11.5 8");
}

:global(.zlio2ybos) {
  d: path("M18.75 8h1a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 16h-1A1.75 1.75 0 0 1 17 14.25v-4.5A1.75 1.75 0 0 1 18.75 8");
}

</style>
