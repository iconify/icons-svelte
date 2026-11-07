<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="yz85cqd5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-off-duocolor" {...props}></Icon>
<style>
:global(.lmxlbqbeq) {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yz85cqd5u) {
  d: path("M5.564 4.564C4.106 5.178 3 6.615 3 9c0 6 9 11 9 11s2.706-1.503 5.15-3.85m2.693-3.307C20.547 11.643 21 10.347 21 9c0-5.34-5.543-5.927-8.173-3.173");
}

</style>
