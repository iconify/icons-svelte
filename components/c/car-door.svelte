<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rt5xcbbip"/><path class="yyp5l0vnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:car-door" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rt5xcbbip) {
  d: path("m3.5 11.5l6.5-8h8.5a2 2 0 0 1 2 2V19a2.5 2.5 0 0 1-2.5 2.5H5.5a2 2 0 0 1-2-2Z");
}

:global(.yyp5l0vnx) {
  d: path("m8 10.5l3.75-4.25h5.75v4.25Zm6.5 3.5h3");
}

</style>
