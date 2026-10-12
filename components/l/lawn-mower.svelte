<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-y59dcnz"/><circle class="m_ubk9bxa"/><circle class="vk0oucc3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lawn-mower" {...props}></Icon>
<style>
:global(.e-y59dcnz) {
  d: path("m8 11.75l-3.25-8.5H3m1.25 13v-2a2.5 2.5 0 0 1 2.5-2.5h8.5a4 4 0 0 1 4 4v.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_ubk9bxa) {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.vk0oucc3w) {
  cx: 16.75px;
  cy: 18.75px;
  r: 2.5px;
}

</style>
