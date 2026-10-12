<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nq_e_2b0z"/><rect class="nzx-9lahs"/><path class="iwhulrnfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fence-wooden" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwhulrnfp) {
  d: path("M6.75 6.5v.01m10.5-.01v.01M2.75 10h18.5m-18.5 5.75h18.5");
}

:global(.nq_e_2b0z) {
  width: 3.5px;
  height: 17.75px;
  x: 5px;
  y: 3.5px;
  rx: 1px;
}

:global(.nzx-9lahs) {
  width: 3.5px;
  height: 17.75px;
  x: 15.5px;
  y: 3.5px;
  rx: 1px;
}

</style>
