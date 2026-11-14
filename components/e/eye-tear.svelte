<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlsnbbbzm"/><path class="l150tfb6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-tear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l150tfb6e) {
  d: path("M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m7 7.75L17.5 19a1.75 1.75 0 1 1-3 0Z");
}

:global(.vlsnbbbzm) {
  d: path("M2.5 9C5 4.75 8.25 3 12 3s7 1.75 9.5 6c-2.5 4.25-5.75 6-9.5 6s-7-1.75-9.5-6");
}

</style>
