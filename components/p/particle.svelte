<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rzyzgqcqn"/><path class="jpsy3j9-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:particle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpsy3j9-d) {
  d: path("M15.18 8.82q.55-3.03 3.71-3.71m-3.71 10.07q.55 3.03 3.71 3.71M8.82 15.18q-.55 3.03-3.71 3.71M8.82 8.82q-.55-3.03-3.71-3.71");
}

:global(.rzyzgqcqn) {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

</style>
