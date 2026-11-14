<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r470zbg-b"/><path class="reu4r-43d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-pin-user" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r470zbg-b) {
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12");
}

:global(.reu4r-43d) {
  d: path("M10.5 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1.25 5C9.75 11.5 10.75 11 12 11s2.25.5 2.75 1.75");
}

</style>
