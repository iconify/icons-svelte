<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s-qcj_9gw"/><path class="lb18hac-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:delivery-time-estimate" {...props}></Icon>
<style>
:global(.lb18hac-a) {
  d: path("M14 8.5V12l2.5 1.5M2 8.5h1.75M2 12h1.75M2 15.5h1.75");
}

:global(.s-qcj_9gw) {
  d: path("M6.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
