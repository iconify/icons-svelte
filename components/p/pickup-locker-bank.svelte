<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hz2ik4b6m"/><path class="k2subul5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pickup-locker-bank" {...props}></Icon>
<style>
:global(.hz2ik4b6m) {
  d: path("M2.5 2.5h19v19h-19Zm6 0v19m7-19v19");
}

:global(.k2subul5b) {
  d: path("M10.25 5h3.5v4.5h-3.5ZM2.5 9h6m-6 6.25h6m7-6.25h6m-6 6.25h6M10.25 14h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
