<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yceyyxb5e"/><path class="ivdr8mbot"/><rect class="il8p-j2nc"/><rect class="rdfjt3bak"/><path class="c-od-jb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:confusion-matrix" {...props}></Icon>
<style>
:global(.c-od-jb3j) {
  d: path("M2.75 7.5V11M7.5 2.75H11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.il8p-j2nc) {
  width: 3px;
  height: 3px;
  x: 7.75px;
  y: 7.75px;
  rx: 1px;
}

:global(.ivdr8mbot) {
  d: path("M13.25 5.25v16m-8-8h16");
}

:global(.rdfjt3bak) {
  width: 3px;
  height: 3px;
  x: 15.75px;
  y: 15.75px;
  rx: 1px;
}

:global(.yceyyxb5e) {
  width: 16px;
  height: 16px;
  x: 5.25px;
  y: 5.25px;
  rx: 2px;
}

</style>
