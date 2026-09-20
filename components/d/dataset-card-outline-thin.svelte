<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkn_9lu9q"/><path class="w2ifj5b6m"/><path class="ctl_2kq5g"/><path class="zpdz8rbaf"/><path class="fymeavbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dataset-card-outline-thin" {...props}></Icon>
<style>
:global(.ctl_2kq5g) {
  d: path("M12 5.5V12");
}

:global(.fymeavbya) {
  d: path("M9 18.5h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tkn_9lu9q) {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.w2ifj5b6m) {
  d: path("M8 7.5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2V10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.zpdz8rbaf) {
  d: path("M9 15.5h6");
}

</style>
