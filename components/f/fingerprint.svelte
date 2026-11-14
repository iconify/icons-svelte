<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zah8ppbcu"/><path class="syp7axonp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fingerprint" {...props}></Icon>
<style>
:global(.syp7axonp) {
  d: path("M7.5 19.5v-7a4.5 4.5 0 0 1 9 0v5M12 21v-8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zah8ppbcu) {
  d: path("M4 16v-3.5a8 8 0 0 1 16 0v3");
}

</style>
