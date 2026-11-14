<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="niq9g_bcr"/><path class="cd52s_yqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:incremental-build" {...props}></Icon>
<style>
:global(.cd52s_yqj) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5m-1 12.25h2.25V19H20v-2.5h2");
}

:global(.niq9g_bcr) {
  d: path("M12.738 21.131L12 21.5L3 17V7l9-4.5L21 7v6.738");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
