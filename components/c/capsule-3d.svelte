<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cb-52l0ci"/><path class="tsqwxqb1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capsule-3d" {...props}></Icon>
<style>
:global(.cb-52l0ci) {
  d: path("M10 2.5h4a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-13a3 3 0 0 1 3-3Z");
}

:global(.tsqwxqb1y) {
  d: path("M7 12a5 1.75 0 0 0 10 0M7 12a5 1.75 0 0 1 10 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
