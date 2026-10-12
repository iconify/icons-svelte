<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="b5g6cpb9d"/><path class="jr3swaciy"/><path class="ii3j1qnxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:carrying-box-sharp" {...props}></Icon>
<style>
:global(.b5g6cpb9d) {
  cx: 12px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.ii3j1qnxb) {
  d: path("M7.5 13.25h9v6.5h-9zm4.5 0v2.5");
}

:global(.jr3swaciy) {
  d: path("M4.75 21.25V10.5h14.5v10.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
