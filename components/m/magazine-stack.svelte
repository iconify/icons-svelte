<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9qrgjqun"/><path class="pi3jpw3dr"/><path class="vsjz_jngy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magazine-stack" {...props}></Icon>
<style>
:global(.l9qrgjqun) {
  d: path("M2.5 7.5h13v14h-13Z");
}

:global(.pi3jpw3dr) {
  d: path("M5 4.75h11.25a2 2 0 0 1 2 2V19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vsjz_jngy) {
  d: path("M7.75 2H19a2 2 0 0 1 2 2v12.25M5.5 11.5h7");
}

</style>
