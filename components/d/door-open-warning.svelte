<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tn2f5sb9a"/><path class="szso97bmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:door-open-warning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.szso97bmb) {
  d: path("M9 7.25h6m-5.5 9.5h5M7.25 9l-4 3.75M16.75 9l4 3.75");
}

:global(.tn2f5sb9a) {
  width: 9.5px;
  height: 18.5px;
  x: 7.25px;
  y: 2.75px;
  rx: 3.5px;
}

</style>
