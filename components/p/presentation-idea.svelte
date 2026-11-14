<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t0fkxsbcm"/><path class="qiw0ivbsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:presentation-idea" {...props}></Icon>
<style>
:global(.qiw0ivbsm) {
  d: path("M10.5 12.5v-1a3 3 0 1 1 3 0v1Z");
}

:global(.t0fkxsbcm) {
  d: path("M2.5 3h19v13h-19ZM7 16l-2 5.5M17 16l2 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
