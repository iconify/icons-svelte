<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jz-1npb_j"/><path class="vpo1iqsnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:monitor-dual" {...props}></Icon>
<style>
:global(.jz-1npb_j) {
  d: path("M8 8h13.5v9H8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vpo1iqsnq) {
  d: path("M5 14h-.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2H15m-.25 13v3.5m-3 0h6");
}

</style>
