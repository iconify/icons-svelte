<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1ij8ibsl"/><path class="b_cr4fbvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:helicopter-front-duocolor-sharp" {...props}></Icon>
<style>
:global(.a1ij8ibsl) {
  stroke-opacity: 0.4;
  d: path("M3 3h18m-9 0v4");
}

:global(.b_cr4fbvi) {
  d: path("M6 13a6 6 0 1 1 12 0v4H6zm2 4v4m8-4v4M6 21h4m4 0h4M6 13h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
