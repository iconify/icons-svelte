<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgjlq_ckg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:particles-vfx" {...props}></Icon>
<style>
:global(.lgjlq_ckg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5q1 6 7 7q-6 1-7 7q-1-6-7-7q6-1 7-7m8-3.5q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3m1 13q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5");
}

</style>
