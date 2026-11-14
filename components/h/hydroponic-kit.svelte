<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yrt_whbhi"/><path class="uqpqd6wlg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hydroponic-kit" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uqpqd6wlg) {
  d: path("M6 17q1.5-1 3 0t3 0t3 0t3 0m-6-8.5V19m0-10.5c0-2.5-2-4-5-4c0 2.5 2 4 5 4Zm0 0c0-2.5 2-4 5-4c0 2.5-2 4-5 4Z");
}

:global(.yrt_whbhi) {
  d: path("M3 12.5h18V21H3Z");
}

</style>
