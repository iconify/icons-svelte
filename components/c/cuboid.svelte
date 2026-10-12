<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abspstbld"/><path class="bldzk2bze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cuboid" {...props}></Icon>
<style>
:global(.abspstbld) {
  d: path("M4.25 10.5h9.5q1.25 0 2.2-.82l3.6-3.11q.95-.82.95.43v5.5q0 1.25-.95 2.07l-3.6 3.11q-.95.82-2.2.82h-9.5Q3 18.5 3 17.25v-5.5q0-1.25 1.25-1.25");
}

:global(.bldzk2bze) {
  d: path("m3.95 9.68l3.6-3.11q.95-.82 2.2-.82h9.5q1.25 0 .3.82l-3.6 3.11q-.95.82-2.2.82h-9.5q-1.25 0-.3-.82M15 11v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
