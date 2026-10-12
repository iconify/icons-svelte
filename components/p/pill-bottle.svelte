<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cb1nrybur"/><rect class="ij8bw_4gc"/><path class="y_2qowbrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pill-bottle" {...props}></Icon>
<style>
:global(.cb1nrybur) {
  width: 12.5px;
  height: 12.25px;
  x: 5.75px;
  y: 9px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ij8bw_4gc) {
  width: 14.5px;
  height: 3.75px;
  x: 4.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.y_2qowbrf) {
  d: path("M12 12.25v5.5M9.25 15h5.5");
}

</style>
