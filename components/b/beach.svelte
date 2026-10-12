<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrk64bchc"/><path class="zc4o49b-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beach" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrk64bchc) {
  d: path("M3.25 11.25a8.75 7.5 0 0 1 17.5 0Z");
}

:global(.zc4o49b-c) {
  d: path("M12 3.75c-1.75 2-2.5 4.75-2.5 7.5m2.5-7.5c1.75 2 2.5 4.75 2.5 7.5m-2.5 0v7.5m-9.25 2.5c3-1.75 6-2.5 9.25-2.5s6.25.75 9.25 2.5");
}

</style>
