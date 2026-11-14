<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y3s3i6f_x"/><path class="s_jt13b0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:card-multiple" {...props}></Icon>
<style>
:global(.s_jt13b0l) {
  d: path("M6 5h13a2.5 2.5 0 0 1 2.5 2.5v8m-19-4h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y3s3i6f_x) {
  d: path("M2.5 8h16v11.5h-16Z");
}

</style>
