<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="egv9mlbmq"/><path class="hbhujobwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:following-list" {...props}></Icon>
<style>
:global(.egv9mlbmq) {
  cx: 7.5px;
  cy: 9.25px;
  r: 3px;
}

:global(.hbhujobwu) {
  d: path("M3.5 20.25h8a.75.75 0 0 0 .75-.75c0-2.6-2.1-4.5-4.75-4.5s-4.75 1.9-4.75 4.5a.75.75 0 0 0 .75.75m12-10.75h5.75M15.5 14h5.75m-5.75 4.5H19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
