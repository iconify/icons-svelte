<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrrfgp3ac"/><path class="sye78vbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:brand-protection" {...props}></Icon>
<style>
:global(.sye78vbzq) {
  d: path("M16.25 17v-1a1.75 1.75 0 0 1 3.5 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xrrfgp3ac) {
  d: path("M12.2 19.5H8.5l-5-7.5l5-7.5h11v7.2M8.25 12h.01M15 17h6v4.5h-6Z");
}

</style>
