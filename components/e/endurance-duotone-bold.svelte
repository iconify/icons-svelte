<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l243prbwj"/><path class="pysw3zbpf"/><path class="esla8ehgu"/><path class="cmt-chbtl"/><path class="iwanrcb5f"/><path class="s97tcsbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:endurance-duotone-bold" {...props}></Icon>
<style>
:global(.cmt-chbtl) {
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
}

:global(.esla8ehgu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 5h4v4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iwanrcb5f) {
  d: path("M15 13V5");
}

:global(.l243prbwj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pysw3zbpf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 13V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s97tcsbyl) {
  d: path("M15 5h4v4h-4");
}

</style>
