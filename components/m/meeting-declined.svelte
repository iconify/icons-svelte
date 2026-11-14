<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rm7-_vbey"/><path class="hwkzlfygx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:meeting-declined" {...props}></Icon>
<style>
:global(.hwkzlfygx) {
  d: path("M7 19.5c0-2.25 1.5-3.5 3.5-3.5s3.5 1.25 3.5 3.5M3 3l18 18");
}

:global(.rm7-_vbey) {
  d: path("M8.4 4.5h13.1v13.1m-5.9 1.9H2.5V6.4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
