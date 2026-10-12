<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlc9a-b8t"/><rect class="tvru1cbqe"/><path class="pkq723bwy"/><rect class="obduvcc6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camping-lantern" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.obduvcc6v) {
  width: 10.5px;
  height: 3.5px;
  x: 6.75px;
  y: 17.75px;
  rx: 1.25px;
}

:global(.pkq723bwy) {
  d: path("M12 15.5c-1 0-1.5-.75-1.5-1.5c0-1 1.5-2.25 1.5-2.25S13.5 13 13.5 14c0 .75-.5 1.5-1.5 1.5");
}

:global(.tvru1cbqe) {
  width: 8.5px;
  height: 9px;
  x: 7.75px;
  y: 8.75px;
  rx: 2px;
}

:global(.vlc9a-b8t) {
  d: path("M9.5 5.5a2.5 2.5 0 0 1 5 0M7.61 8.09l1.03-1.93Q9 5.5 9.75 5.5h4.5q.75 0 1.11.66l1.03 1.93q.36.66-.39.66H8q-.75 0-.39-.66");
}

</style>
