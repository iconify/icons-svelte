<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k544vu3cf"/><path class="y8j48jscp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ember" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k544vu3cf) {
  d: path("M12 8.5c2.5 2.5 5.5 5 5.5 7.5a5.5 5.5 0 0 1-11 0c0-2.5 3-5 5.5-7.5");
}

:global(.y8j48jscp) {
  d: path("M12 13.5c1.25 1.25 2 2.25 2 3a2 2 0 0 1-4 0c0-.75.75-1.75 2-3M8.5 5.75l-1-3m8 3.5l1-3");
}

</style>
