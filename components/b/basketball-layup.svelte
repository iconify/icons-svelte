<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="edqxoqchc"/><path class="btwpbfbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:basketball-layup" {...props}></Icon>
<style>
:global(.btwpbfbsz) {
  d: path("M3.75 3.75Q7 7 3.75 10.25m6.5-6.5Q7 7 10.25 10.25M9.5 14h12M11 14l2 7h5l2-7");
}

:global(.edqxoqchc) {
  d: path("M2.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0 0h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
