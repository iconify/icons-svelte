<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="krauzq_cj"/><path class="k36mcm39v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:die-cutter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k36mcm39v) {
  d: path("m12.75 8.25l.388.905a1.5 1.5 0 0 0 1.279.906l.958.064a.752.752 0 0 1 .431 1.328l-.82.684a1.5 1.5 0 0 0-.489 1.539l.261.98a.76.76 0 0 1-1.133.844l-.839-.516a1.5 1.5 0 0 0-1.572 0l-.839.516a.76.76 0 0 1-1.133-.844l.261-.98a1.5 1.5 0 0 0-.489-1.539l-.82-.684a.752.752 0 0 1 .431-1.328l.958-.064a1.5 1.5 0 0 0 1.279-.906l.388-.905a.816.816 0 0 1 1.5 0");
}

:global(.krauzq_cj) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-11A3.5 3.5 0 0 1 6.5 3");
}

</style>
