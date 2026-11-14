<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="klnfn0b3h"/><path class="e9_hoibmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lab-coat-person" {...props}></Icon>
<style>
:global(.e9_hoibmi) {
  d: path("m9 14.75l3 4.75l3-4.75m-3 4.75v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klnfn0b3h) {
  d: path("M8.25 6.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M4 21.5V19c0-2.75 3-4.75 8-4.75s8 2 8 4.75v2.5");
}

</style>
