<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qo05omb1p"/><path class="q_5_1kbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lab-schedule" {...props}></Icon>
<style>
:global(.q_5_1kbkt) {
  d: path("M6.5 10.5h11V14h-11Zm0 6.5h6");
}

:global(.qo05omb1p) {
  d: path("M3 4h18v17.5H3Zm5-1.5V6m8-3.5V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
