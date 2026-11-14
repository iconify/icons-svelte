<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bypl4qbjt"/><path class="oet-3dk_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:patient-transport" {...props}></Icon>
<style>
:global(.bypl4qbjt) {
  d: path("M6 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 8v4.5h5.5l2.5 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oet-3dk_w) {
  d: path("M12.505 12.345a5.5 5.5 0 1 1-9.01 0M16 5.5h5m-2-2l2 2l-2 2");
}

</style>
