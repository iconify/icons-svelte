<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ssdt96b_e"/><path class="xmms1nfsq"/><path class="qcyrzdcmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bangles-stack" {...props}></Icon>
<style>
:global(.qcyrzdcmv) {
  d: path("M6.5 17a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

:global(.ssdt96b_e) {
  d: path("M2.5 7a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xmms1nfsq) {
  d: path("M4.5 12a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

</style>
