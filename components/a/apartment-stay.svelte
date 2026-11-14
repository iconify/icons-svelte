<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qj591t_mk"/><path class="tf-b6mb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:apartment-stay" {...props}></Icon>
<style>
:global(.qj591t_mk) {
  d: path("M12 21.5H3.5v-19H15v12.9M6.75 6.5h.5m4 0h.5m-5 4h.5m4 0h.5m-5 4h.5m4 0h.5");
}

:global(.tf-b6mb8c) {
  d: path("M7.75 21.5V18h3v3.5m3.75-1.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
