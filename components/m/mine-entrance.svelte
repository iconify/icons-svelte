<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sge8t85_o"/><path class="m_uc3fb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mine-entrance" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_uc3fb9e) {
  d: path("M6.5 17.5V11a5.5 5.5 0 0 1 11 0v6.5m-9.5 4l2.25-7.5M16 21.5L13.75 14");
}

:global(.sge8t85_o) {
  d: path("M6.5 17.5h-4v-13a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v13h-4");
}

</style>
