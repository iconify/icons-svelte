<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5czi6rdr"/><path class="azs8m69dm"/><path class="kgpu6-15k"/><path class="rfdwl-jei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-escalate-outline-thin" {...props}></Icon>
<style>
:global(.azs8m69dm) {
  d: path("m14 5 -2.5 2.5H14L11.5 10");
}

:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kgpu6-15k) {
  d: path("m10 15.5 2 -2 2 2");
}

:global(.rfdwl-jei) {
  d: path("m10 18.5 2 -2 2 2");
}

</style>
