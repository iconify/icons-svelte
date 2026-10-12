<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ceut2u0ve"/><rect class="b4-xgxb0m"/><path class="z5aq1abnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:deploy-arrow" {...props}></Icon>
<style>
:global(.b4-xgxb0m) {
  width: 17.5px;
  height: 9.75px;
  x: 3.25px;
  y: 11.5px;
  rx: 2px;
}

:global(.ceut2u0ve) {
  d: path("M12 9.25v-6.5M8.75 6L12 2.75L15.25 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z5aq1abnn) {
  d: path("M3.25 16.38h17.5M7 13.94h3m-3 4.87h3");
}

</style>
