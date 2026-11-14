<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f82s-dwsz"/><path class="phjc2aclq"/><path class="bmwgh671v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:orchid" {...props}></Icon>
<style>
:global(.bmwgh671v) {
  d: path("M12 11c-4 1.5-5 6-3 9.5q3-2 6 0c2-3.5 1-8-3-9.5");
}

:global(.f82s-dwsz) {
  d: path("M12 11c-2.5-3-2-6.5 0-8.5c2 2 2.5 5.5 0 8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.phjc2aclq) {
  d: path("M12 11c-3-4-8-4-9-1c1 3.5 6 3.5 9 1m0 0c3-4 8-4 9-1c-1 3.5-6 3.5-9 1");
}

</style>
