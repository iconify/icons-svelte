<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f30f0xbjf"/><path class="sd-tcbibe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bundle-analyzer" {...props}></Icon>
<style>
:global(.f30f0xbjf) {
  d: path("M2.5 7.5H17v14H2.5Zm0 0L7 3h14.5v14L17 21.5m0-14L21.5 3");
}

:global(.sd-tcbibe) {
  d: path("M5.25 14.25h4.5v4.5h-4.5Zm4.5 1.5h3v3h-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
