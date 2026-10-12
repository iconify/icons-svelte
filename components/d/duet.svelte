<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="phjvadcnz"/><path class="nd7y81b9b"/><circle class="v4wf3czoy"/><path class="k96j4-b7r"/><circle class="phidi_btw"/><path class="b3_k96hhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:duet" {...props}></Icon>
<style>
:global(.b3_k96hhs) {
  d: path("M14.1 16a2.5 2.5 0 0 1 5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k96j4-b7r) {
  d: path("M4.9 16a2.5 2.5 0 0 1 5 0");
}

:global(.nd7y81b9b) {
  d: path("M12 3.75v16.5");
}

:global(.phidi_btw) {
  cx: 16.6px;
  cy: 10px;
  r: 1.75px;
}

:global(.phjvadcnz) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 3px;
}

:global(.v4wf3czoy) {
  cx: 7.4px;
  cy: 10px;
  r: 1.75px;
}

</style>
