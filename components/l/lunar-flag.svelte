<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owvim6bvs"/><rect class="z595ebbvw"/><path class="md5itublp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lunar-flag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.md5itublp) {
  d: path("M2.75 21.25C5.25 19.5 8.25 19 12 19s6.75.5 9.25 2.25");
}

:global(.owvim6bvs) {
  d: path("M6.5 2.75v16.5");
}

:global(.z595ebbvw) {
  width: 12.5px;
  height: 7.5px;
  x: 8.75px;
  y: 3px;
  rx: 1px;
}

</style>
