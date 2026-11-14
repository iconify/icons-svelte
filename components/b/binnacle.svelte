<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b28ohdctn"/><path class="wewzdbckz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:binnacle" {...props}></Icon>
<style>
:global(.b28ohdctn) {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wewzdbckz) {
  d: path("M10.75 13.5L10 19H7.5v2.5h9V19H14l-.75-5.5m-.625-6.875l.343.754a1.5 1.5 0 0 1 0 1.242l-.343.754a.687.687 0 0 1-1.25 0l-.343-.754a1.5 1.5 0 0 1 0-1.242l.343-.754a.687.687 0 0 1 1.25 0");
}

</style>
