<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k07rmusbs"/><path class="jm6jpnbxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rooftop-site" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jm6jpnbxn) {
  d: path("M10 21.5V17h4v4.5M7 11V8M5.5 2.5h3V8h-3ZM17 11V8m-1.5-5.5h3V8h-3Z");
}

:global(.k07rmusbs) {
  d: path("M6.125 11h11.75a2.625 2.625 0 0 1 2.625 2.625v5.25a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875v-5.25A2.625 2.625 0 0 1 6.125 11");
}

</style>
