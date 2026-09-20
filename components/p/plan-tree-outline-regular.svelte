<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ffl_tubrp"/><path class="fl42iabgs"/><path class="s4opvo9pz"/><path class="siocq_7mf"/><path class="iic1bs66d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plan-tree-outline-regular" {...props}></Icon>
<style>
:global(.ffl_tubrp) {
  d: path("M7 6.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2");
}

:global(.fl42iabgs) {
  d: path("M12 8.5V12");
}

:global(.iic1bs66d) {
  d: path("M14.5 17.75a2.25 2.25 0 0 1 2.25 -2.25h2.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 20h-2.5a2.25 2.25 0 0 1 -2.25 -2.25");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s4opvo9pz) {
  d: path("M6 15.5V12h12v3.5");
}

:global(.siocq_7mf) {
  d: path("M2.5 17.75a2.25 2.25 0 0 1 2.25 -2.25h2.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 7.25 20h-2.5a2.25 2.25 0 0 1 -2.25 -2.25");
}

</style>
