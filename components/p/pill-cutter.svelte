<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3-74l2ee"/><rect class="d4fhxdbfu"/><rect class="q52cjmb4y"/><path class="a83s16bte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pill-cutter" {...props}></Icon>
<style>
:global(.a83s16bte) {
  d: path("M12 14.75v3.75");
}

:global(.d4fhxdbfu) {
  width: 18.5px;
  height: 8.25px;
  x: 2.75px;
  y: 12.5px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q52cjmb4y) {
  width: 6.5px;
  height: 3.75px;
  x: 8.75px;
  y: 14.75px;
  rx: 1.75px;
}

:global(.x3-74l2ee) {
  d: path("M20.28 10.02L4.22 6.23Q3.25 6 3.25 5V4q0-1 .97-.77l16.06 3.79q.97.23.97 1.23v1q0 1-.97.77");
}

</style>
