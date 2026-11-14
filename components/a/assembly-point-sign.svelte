<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgnun8byb"/><path class="wl61jtfpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:assembly-point-sign" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wl61jtfpr) {
  d: path("M5.75 14v-1.5a1.5 1.5 0 0 1 3 0V14m1.75 0v-1.5a1.5 1.5 0 0 1 3 0V14m1.75 0v-1.5a1.5 1.5 0 0 1 3 0V14");
}

:global(.zgnun8byb) {
  d: path("M2.5 2.5h19v15h-19Zm9.5 15v4m-4.75-13h.01m4.74 0h.01m4.74 0h.01");
}

</style>
