<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r470zbg-b"/><path class="g3hconb4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-pin-heart" {...props}></Icon>
<style>
:global(.g3hconb4n) {
  d: path("M12 12s-2.75-1.5-2.75-3.5c0-.75.75-1.5 1.5-1.5c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.5c0 2-2.75 3.5-2.75 3.5");
}

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

</style>
