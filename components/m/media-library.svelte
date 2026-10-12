<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jyzbpctkd"/><rect class="wox5_pmda"/><path class="xjbm2mbab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:media-library" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyzbpctkd) {
  d: path("M4.25 3.75v16.5m4-16.5v16.5");
}

:global(.wox5_pmda) {
  width: 10px;
  height: 13px;
  x: 11.25px;
  y: 7.25px;
  rx: 2.5px;
}

:global(.xjbm2mbab) {
  d: path("m15.33 11.64l2.59 1.72q.58.39 0 .78l-2.59 1.72q-.58.39-.58-.31v-3.6q0-.7.58-.31");
}

</style>
