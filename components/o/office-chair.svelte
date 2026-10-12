<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r9co1dboz"/><path class="yx9ptr6oa"/><rect class="cpmswccvi"/><path class="zy9xxactq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:office-chair" {...props}></Icon>
<style>
:global(.cpmswccvi) {
  width: 14.5px;
  height: 3px;
  x: 4.75px;
  y: 13px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r9co1dboz) {
  width: 9.5px;
  height: 7px;
  x: 7.25px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.yx9ptr6oa) {
  d: path("M12 9.75V13");
}

:global(.zy9xxactq) {
  d: path("M12 16v2.75m-5.75 2.5l5.75-2.5l5.75 2.5");
}

</style>
