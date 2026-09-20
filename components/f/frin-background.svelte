<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="lrljk3brc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:frin-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lrljk3brc) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.38 4h13.24l-1.252 4.966h-5.92v2.758h5.705l-1.076 4.414h-4.629V20H5.38zm6.068 11.586h4.194l.805-3.31h-4.999zm-.551-3.862V8.828l-4.966-4v6.896zm-4.966.806v6.918h4.966v-3.443zm4.966 2.803v-3.057H6.533zM6.483 4.551h4.414v3.586zm4.965 3.862h5.501l.954-3.862h-6.455z");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
