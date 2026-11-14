<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="urfg_mbrt"/><path class="jqszqpbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quickstart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jqszqpbdg) {
  d: path("m8 11.5l-3 3V18l3-2m8-4.5l3 3V18l-3-2m-5.25-7a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M12 19v3");
}

:global(.urfg_mbrt) {
  d: path("M12 2c3.5 2.5 4.5 6.5 4 14H8c-.5-7.5.5-11.5 4-14");
}

</style>
