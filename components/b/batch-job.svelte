<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bg8_h7g_f"/><path class="gtg72fbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:batch-job" {...props}></Icon>
<style>
:global(.bg8_h7g_f) {
  d: path("M12.2 21.5H2.5v-12h16v3.7m-14-6.7h12m-10-3h8");
}

:global(.gtg72fbwi) {
  d: path("m15 14.5l6.5 3.5l-6.5 3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
