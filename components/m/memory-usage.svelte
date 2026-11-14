<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t1bejqw1l"/><path class="dc14kuehf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:memory-usage" {...props}></Icon>
<style>
:global(.dc14kuehf) {
  d: path("M5.5 8.25H10v4.5H5.5Zm8.5 0h4.5v4.5H14ZM5.5 15.5v3m3.5-3v3m6-3v3m3.5-3v3");
}

:global(.t1bejqw1l) {
  d: path("M2.5 5.5h19v10h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
