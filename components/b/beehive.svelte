<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yojdlhi-y"/><path class="jzc1_qb_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beehive" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jzc1_qb_i) {
  d: path("M10.25 21.25v-1a1.75 1.75 0 0 1 3.5 0v1");
}

:global(.yojdlhi-y) {
  d: path("M4.25 21.25q0-2.25.75-4.5c1-7.5 3.5-12 7-12s6 4.5 7 12q.75 2.25.75 4.5Zm2.65-12h10.2M5.68 13h12.64M10 16.75H5m9 0h5");
}

</style>
