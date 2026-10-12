<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2gv24b8y"/><path class="xnoe9tbxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kilt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p2gv24b8y) {
  d: path("M7 3.5h10q1 0 1.13.99l1.99 14.77q.13.99-.87.99H4.75q-1 0-.87-.99L5.87 4.49Q6 3.5 7 3.5m-.75 3h11.5M8.5 15v4.5m7-4.5v4.5");
}

:global(.xnoe9tbxs) {
  d: path("M11 9.5h2q.75 0 .87.74l.51 3.02q.12.74-.49 1.17l-1.28.89q-.61.43-1.22 0l-1.28-.89q-.61-.43-.49-1.17l.51-3.02q.12-.74.87-.74");
}

</style>
