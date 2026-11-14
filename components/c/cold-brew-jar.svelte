<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_nmvetqo"/><path class="xdpzootib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cold-brew-jar" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xdpzootib) {
  d: path("M10 5.5v8q0 2 2 2t2-2v-8m-9 13h14");
}

:global(.y_nmvetqo) {
  d: path("M7 2.5h10v3H7Zm.5 3V7Q5 8 5 10.5V19q0 2.5 2.5 2.5h9q2.5 0 2.5-2.5v-8.5Q19 8 16.5 7V5.5");
}

</style>
