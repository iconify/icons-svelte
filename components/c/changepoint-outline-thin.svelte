<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="loqr5yt1s"/><path class="g-wxd1xvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:changepoint-outline-thin" {...props}></Icon>
<style>
:global(.g-wxd1xvy) {
  d: path("M12 5v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.loqr5yt1s) {
  d: path("M4 10h8l7 7");
}

</style>
