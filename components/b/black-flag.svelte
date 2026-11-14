<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2uobqk4k"/><path class="hh633abth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:black-flag" {...props}></Icon>
<style>
:global(.a2uobqk4k) {
  fill: currentColor;
  d: path("M9.25 2.5h5.5a1.75 1.75 0 0 1 1.75 1.75v7.5a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-7.5A1.75 1.75 0 0 1 9.25 2.5");
}

:global(.hh633abth) {
  d: path("M12 13.5v5m-3.5 3l3.5-3l3.5 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
