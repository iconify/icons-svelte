<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cu4tpzh0g"/><path class="s7forcpna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:filter-availability" {...props}></Icon>
<style>
:global(.cu4tpzh0g) {
  d: path("M2.5 2.5h15V7h-15ZM4 7v9.5q0 1 1 1h7.586M16 11.928V7");
}

:global(.s7forcpna) {
  d: path("m7 12l2.25 2.25l.411-.462m1.594-1.794L13.25 9.75m.75 5h7.25l-2.75 3.5v3l-1.75-1v-2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
