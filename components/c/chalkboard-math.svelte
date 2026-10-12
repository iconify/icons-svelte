<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xqm19zbyf"/><path class="kzuym2bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chalkboard-math" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kzuym2bho) {
  d: path("M6.25 9.5h3.5M8 7.75v3.5m4.75-2.75h5m-5 2.25h5M12 16.25v5m-3.5 0h7");
}

:global(.xqm19zbyf) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
