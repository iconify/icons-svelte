<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gg_xxm92g"/><path class="cqgxiwcha"/><rect class="d_45zfa7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:briefcase" {...props}></Icon>
<style>
:global(.cqgxiwcha) {
  d: path("M8.75 7.25v-1.5a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v1.5m-12.5 5.5h7.5m3.5 0h7.5");
}

:global(.d_45zfa7w) {
  width: 3.5px;
  height: 3px;
  x: 10.25px;
  y: 11.25px;
  rx: 1px;
}

:global(.gg_xxm92g) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
