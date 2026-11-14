<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6wu_qbyi"/><path class="i9f_qzbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bolt-and-nut" {...props}></Icon>
<style>
:global(.h6wu_qbyi) {
  d: path("M3 2.5h8v4H3Zm2 4v13a2 2 0 0 0 4 0v-13m8 3l3.897 2.25v4.5L17 18.5l-3.897-2.25v-4.5Zm-12 1l4-1m-4 4l4-1m-4 4l4-1");
}

:global(.i9f_qzbgs) {
  d: path("M15.25 14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
