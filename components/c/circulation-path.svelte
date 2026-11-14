<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uu-y5wjts"/><path class="iv1dksbnm"/><path class="kjz04c4oa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circulation-path" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iv1dksbnm) {
  d: path("M14 4.5a11 11 0 0 1-1 3.75M11.75 10A11 11 0 0 1 9 12.75m-2 1a11 11 0 0 1-2.5.75");
}

:global(.kjz04c4oa) {
  d: path("m5.625 13.375l-.064.064a1.5 1.5 0 0 0 0 2.122l.064.064a.659.659 0 0 0 1.125-.466v-1.318a.659.659 0 0 0-1.125-.466");
}

:global(.uu-y5wjts) {
  d: path("M3 12V3.5h8.5m5 0H21v17H3V17");
}

</style>
