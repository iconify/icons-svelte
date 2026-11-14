<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j79_mewpd"/><path class="sgr4h-qkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audio-sync" {...props}></Icon>
<style>
:global(.j79_mewpd) {
  d: path("M2.5 9.5h19V21h-19Zm0 0V6.75L19.75 3l.75 3.25Z");
}

:global(.sgr4h-qkq) {
  d: path("M5.5 15.25H8l1.5-2.75l2 5.5l2-5.5l2 5l1-2.25h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
