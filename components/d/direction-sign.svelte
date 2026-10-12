<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yw5d9xb9r"/><path class="tduyi_bww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:direction-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tduyi_bww) {
  d: path("M7.5 11.25v-1.5a2 2 0 0 1 2-2h7M14.25 5.5l2.25 2.25L14.25 10M12 14.25v7");
}

:global(.yw5d9xb9r) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

</style>
