<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghtz8h6wm"/><path class="bzumcubcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rotate-ccw" {...props}></Icon>
<style>
:global(.bzumcubcq) {
  d: path("m15 2.5l-3 3l3 3");
}

:global(.ghtz8h6wm) {
  d: path("M12 5.5a7.5 7.5 0 1 1-6.495 3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
