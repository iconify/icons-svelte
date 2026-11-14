<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t13eeubsk"/><path class="i209rv7rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:browser-security" {...props}></Icon>
<style>
:global(.i209rv7rw) {
  d: path("M10.25 13.25v-1a1.75 1.75 0 0 1 3.5 0v1m-5 0h6.5v5h-6.5Z");
}

:global(.t13eeubsk) {
  d: path("M2.5 3h19v18h-19Zm0 4.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
