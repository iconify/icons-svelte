<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qr6qwbcrg"/><path class="yu5xb2b3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bell-garland" {...props}></Icon>
<style>
:global(.qr6qwbcrg) {
  d: path("M2.5 6q9.5 8 19 0M5 7.75V9.5m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yu5xb2b3m) {
  d: path("M12 10v2m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0m6-9.25V9.5m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0");
}

</style>
