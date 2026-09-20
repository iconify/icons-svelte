<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cqvf5hngw"/><path class="e-2lvb01c"/><path class="jaf3fnb5e"/><path class="j4csr4mvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-theft-duotone-thin" {...props}></Icon>
<style>
:global(.cqvf5hngw) {
  fill: currentColor;
  d: path("M10.5 7H13a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-4l3 -3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e-2lvb01c) {
  d: path("M10.5 7H13a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-4l3 -3h2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4csr4mvr) {
  d: path("M19.5 9.5 22 12l-2.5 2.5");
}

:global(.jaf3fnb5e) {
  d: path("M17.5 12H20");
}

</style>
