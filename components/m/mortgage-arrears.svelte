<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pklt6v8oy"/><path class="ofp0jdbkc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-arrears" {...props}></Icon>
<style>
:global(.ofp0jdbkc) {
  d: path("M16 7V4h2v4.75m0 5.75v4m0 2.75h.01");
}

:global(.pklt6v8oy) {
  d: path("M15.16 20.5H4v-10l8-7l8 7v1.24");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
