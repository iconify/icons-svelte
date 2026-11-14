<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sish69csd"/><path class="k_0gjoo3n"/><path class="rpeo7dbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:racing-replay" {...props}></Icon>
<style>
:global(.k_0gjoo3n) {
  d: path("m9 7l5 3l-5 3Zm5.75 11A3.25 3.25 0 1 1 18 21.25");
}

:global(.rpeo7dbfw) {
  d: path("M19.25 13.5L18 14.75L19.25 16");
}

:global(.sish69csd) {
  d: path("M12.1 16.5H2.5v-13h17v6.3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
