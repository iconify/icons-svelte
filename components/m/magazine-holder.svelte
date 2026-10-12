<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qyqf4qbqp"/><rect class="fdilnhb6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magazine-holder" {...props}></Icon>
<style>
:global(.fdilnhb6a) {
  width: 7.5px;
  height: 4px;
  x: 8.25px;
  y: 14.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qyqf4qbqp) {
  d: path("M4.75 19.75v-6.5q0-1.5 1.06-2.56l6.88-6.88q1.06-1.06 2.56-1.06h2.5q1.5 0 1.5 1.5v15.5q0 1.5-1.5 1.5H6.25q-1.5 0-1.5-1.5");
}

</style>
