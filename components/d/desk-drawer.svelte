<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t4q52jb4q"/><path class="nhfjb7bui"/><rect class="php90ub8b"/><path class="lix45-bxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:desk-drawer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lix45-bxm) {
  d: path("M11 12.5h2.5");
}

:global(.nhfjb7bui) {
  d: path("M4.75 6.75v14.5m14.5-14.5v14.5");
}

:global(.php90ub8b) {
  width: 8px;
  height: 5.5px;
  x: 8.25px;
  y: 9.75px;
  rx: 1px;
}

:global(.t4q52jb4q) {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 1.5px;
}

</style>
