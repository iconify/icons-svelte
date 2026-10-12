<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="i9tm6qb-c"/><circle class="i_j3w8q_a"/><path class="jho7f84ae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-html" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_j3w8q_a) {
  cx: 12px;
  cy: 14.75px;
  r: 3.75px;
}

:global(.i9tm6qb-c) {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5");
}

:global(.jho7f84ae) {
  d: path("M8.25 14.75h7.5M12 11c-1.6 2.2-1.6 5.3 0 7.5c1.6-2.2 1.6-5.3 0-7.5");
}

:global(.jz9wy2bsc) {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

</style>
