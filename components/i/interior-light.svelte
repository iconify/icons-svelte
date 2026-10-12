<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iodyokm9u"/><path class="c-tz7tywd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:interior-light" {...props}></Icon>
<style>
:global(.c-tz7tywd) {
  d: path("M8.75 8.25h6.5a3.25 3.25 0 0 1-6.5 0m3.25 6v2.5M8.25 13.5l-1.5 1.75m9-1.75l1.5 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iodyokm9u) {
  d: path("M2.75 20.25V13.5c0-5 4-8.75 9.25-8.75s9.25 3.75 9.25 8.75v6.75");
}

</style>
