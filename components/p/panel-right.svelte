<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m2_9-pz2k"/><path class="zub4acc2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:panel-right" {...props}></Icon>
<style>
:global(.m2_9-pz2k) {
  d: path("M2.5 3.5h19v17h-19Zm12.5 0v17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zub4acc2g) {
  d: path("m7.5 9l3 3l-3 3");
}

</style>
