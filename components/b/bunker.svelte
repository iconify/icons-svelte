<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tg8ry4zls"/><path class="r0kksx0xa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bunker" {...props}></Icon>
<style>
:global(.r0kksx0xa) {
  d: path("M9.5 17v-3a2.5 2.5 0 0 1 5 0v3");
}

:global(.tg8ry4zls) {
  d: path("M3.5 17a8.5 9 0 0 1 17 0m-18 0h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
