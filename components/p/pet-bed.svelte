<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ec5uzhbiq"/><path class="ejg2llban"/><path class="f1x-jicox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pet-bed" {...props}></Icon>
<style>
:global(.ec5uzhbiq) {
  d: path("M2.5 11a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0");
}

:global(.ejg2llban) {
  d: path("M2.5 11v3a9.5 6 0 0 0 19 0v-3");
}

:global(.f1x-jicox) {
  d: path("M7 10.25a5 2.5 0 1 0 10 0a5 2.5 0 1 0-10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
