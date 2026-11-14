<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qmsr1mb9y"/><path class="qx-347bal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-assembly-board" {...props}></Icon>
<style>
:global(.qmsr1mb9y) {
  d: path("M3 2.5h18V16H3ZM12 16v5.5m-3.5 0h7");
}

:global(.qx-347bal) {
  d: path("M12 5.5c2.25 2 3 3.5 3 4.75a3 3 0 0 1-6 0C9 9 9.75 7.5 12 5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
