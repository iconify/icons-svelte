<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ekggvtblj"/><circle class="v1ocdgb7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blend-mode" {...props}></Icon>
<style>
:global(.ekggvtblj) {
  cx: 8.75px;
  cy: 12px;
  r: 6px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v1ocdgb7u) {
  cx: 15.25px;
  cy: 12px;
  r: 6px;
}

</style>
