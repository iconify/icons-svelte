<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmg0w7bnn"/><rect class="wjsu1vbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:plumbing-pipe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pmg0w7bnn) {
  d: path("M8 10H3.75a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1H8m8-4h4.25a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H16m-6 2.75v3.5a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1v-3.5");
}

:global(.wjsu1vbnz) {
  width: 8px;
  height: 9.25px;
  x: 8px;
  y: 7.5px;
  rx: 1.25px;
}

</style>
