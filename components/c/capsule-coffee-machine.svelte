<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3t7nhbad"/><path class="bu-y_q2yb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capsule-coffee-machine" {...props}></Icon>
<style>
:global(.bu-y_q2yb) {
  d: path("M6 15.25v3.25a3 3 0 0 0 3 3h1a3 3 0 0 0 3-3v-3.25M7 2.5h5v3H7Z");
}

:global(.e3t7nhbad) {
  d: path("M19.5 21.5V10.25a2 2 0 0 0-2-2h-11a2 2 0 0 0-2 2v.25a2 2 0 0 0 2 2h9.25v9M3 21.5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
