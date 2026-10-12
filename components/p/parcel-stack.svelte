<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e7pn7_4fj"/><path class="c1x_5j8dh"/><rect class="wahfdpbcu"/><path class="o6m-9jsvd"/><rect class="lsk5fmbpq"/><path class="elcndio9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parcel-stack" {...props}></Icon>
<style>
:global(.c1x_5j8dh) {
  d: path("M12 14.5v2.75");
}

:global(.e7pn7_4fj) {
  width: 17.5px;
  height: 6.75px;
  x: 3.25px;
  y: 14.5px;
  rx: 1.25px;
}

:global(.elcndio9a) {
  d: path("M12 2.75v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsk5fmbpq) {
  width: 7px;
  height: 6px;
  x: 8.5px;
  y: 2.75px;
  rx: 0.75px;
}

:global(.o6m-9jsvd) {
  d: path("M12 8.75v2");
}

:global(.wahfdpbcu) {
  width: 12.5px;
  height: 5.75px;
  x: 5.75px;
  y: 8.75px;
  rx: 1px;
}

</style>
