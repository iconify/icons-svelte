<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nj5ucobzf"/><circle class="j3jribyxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eclipse" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3jribyxk) {
  cx: 14.75px;
  cy: 9.25px;
  r: 6.5px;
}

:global(.nj5ucobzf) {
  cx: 9.75px;
  cy: 14.25px;
  r: 7px;
}

</style>
