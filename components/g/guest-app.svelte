<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v4vofccge"/><path class="ncp2-gmcj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:guest-app" {...props}></Icon>
<style>
:global(.ncp2-gmcj) {
  d: path("M8.5 13.5L12 10l3.5 3.5V18h-7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v4vofccge) {
  d: path("M5.5 2.5h13v19h-13Zm5 3h3");
}

</style>
