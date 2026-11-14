<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eshuf8bir"/><path class="f-kroobnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-sandbox" {...props}></Icon>
<style>
:global(.eshuf8bir) {
  d: path("M6 3h12v13H6Z");
}

:global(.f-kroobnx) {
  d: path("M3 13v5.5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V13M10.5 7L8.75 9.5L10.5 12m3-5l1.75 2.5L13.5 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
