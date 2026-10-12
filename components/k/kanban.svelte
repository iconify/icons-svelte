<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qb3606bui"/><rect class="b90xpb3rx"/><rect class="a3scabq7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kanban" {...props}></Icon>
<style>
:global(.a3scabq7d) {
  width: 4px;
  height: 8.5px;
  x: 17px;
  y: 3px;
  rx: 1.5px;
}

:global(.b90xpb3rx) {
  width: 4px;
  height: 18px;
  x: 10px;
  y: 3px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qb3606bui) {
  width: 4px;
  height: 13px;
  x: 3px;
  y: 3px;
  rx: 1.5px;
}

</style>
