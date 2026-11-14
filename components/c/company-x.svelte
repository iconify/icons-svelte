<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ki94lccxg"/><path class="k-464w6np"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:company-x" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-464w6np) {
  d: path("M9.5 21.5v-4h3v4m0-15h.01M12.5 11h.01m2.99 4.5l5 5m0-5l-5 5");
}

:global(.ki94lccxg) {
  d: path("M12.9 21.5H3V9h5V2.5h9v10.6");
}

</style>
