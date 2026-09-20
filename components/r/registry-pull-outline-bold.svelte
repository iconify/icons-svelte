<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z-ephs7jm"/><path class="aho6qjb9y"/><path class="s229edbfl"/><path class="q3srlnbfr"/><path class="fo_ekznwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:registry-pull-outline-bold" {...props}></Icon>
<style>
:global(.aho6qjb9y) {
  d: path("M8 10v9");
}

:global(.fo_ekznwu) {
  d: path("M9.5 4.5 12 2l2.5 2.5");
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s229edbfl) {
  d: path("M15 10v9");
}

:global(.z-ephs7jm) {
  d: path("M2 12a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
