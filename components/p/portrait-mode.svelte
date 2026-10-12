<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk0qikjba"/><circle class="drtvz1btn"/><path class="ygyw9ob-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:portrait-mode" {...props}></Icon>
<style>
:global(.drtvz1btn) {
  cx: 12px;
  cy: 8.5px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vk0qikjba) {
  d: path("M4.75 8V5.25a1.5 1.5 0 0 1 1.5-1.5H9m6 0h2.75a1.5 1.5 0 0 1 1.5 1.5V8m0 8v2.75a1.5 1.5 0 0 1-1.5 1.5H15m-6 0H6.25a1.5 1.5 0 0 1-1.5-1.5V16");
}

:global(.ygyw9ob-w) {
  d: path("M7.75 17.5a4.25 4.25 0 0 1 8.5 0Z");
}

</style>
