<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1kobinmz"/><path class="pw5240eqf"/><path class="wxrlulnmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crop-photo" {...props}></Icon>
<style>
:global(.b1kobinmz) {
  d: path("M6.75 2.75v12.5a2 2 0 0 0 2 2h12.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pw5240eqf) {
  d: path("M2.75 6.75h12.5a2 2 0 0 1 2 2v12.5");
}

:global(.wxrlulnmd) {
  d: path("m9.66 13.87l1.93-2.99q.41-.63.82 0l1.93 2.99q.41.63-.34.63h-4q-.75 0-.34-.63");
}

</style>
