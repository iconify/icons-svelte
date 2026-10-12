<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kqef4tbqv"/><path class="jedknxkfu"/><circle class="l1sa2pbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jhumka-sharp" {...props}></Icon>
<style>
:global(.jedknxkfu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5v2m-6 6a6 6 0 0 1 12 0Zm6 0v3.25");
}

:global(.kqef4tbqv) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01");
}

:global(.l1sa2pbgo) {
  cx: 12px;
  cy: 18.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
