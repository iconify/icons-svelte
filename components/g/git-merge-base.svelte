<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="os96kc9og"/><path class="wsa8k1bzc"/><path class="lmcqfkbja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:git-merge-base" {...props}></Icon>
<style>
:global(.lmcqfkbja) {
  fill: currentColor;
  d: path("M10 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.os96kc9og) {
  d: path("M4 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wsa8k1bzc) {
  d: path("M6 7v1.5c0 3 6 3.5 6 6.5v2m6-10v1.5c0 3-6 3.5-6 6.5");
}

</style>
