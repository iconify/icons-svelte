<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ilimuxb1a"/><path class="p9faghb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-trampoline" {...props}></Icon>
<style>
:global(.ilimuxb1a) {
  d: path("M2.5 12.5a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0Z");
}

:global(.p9faghb0e) {
  d: path("m4.5 14.75l1 5.75h2l1-4.75m11-1l-1 5.75h-2l-1-4.75M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
