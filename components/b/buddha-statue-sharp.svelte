<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u1w-djb2c"/><circle class="b36niz7vv"/><path class="a8ievxbeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:buddha-statue-sharp" {...props}></Icon>
<style>
:global(.a8ievxbeq) {
  d: path("M12 12.5h3.438l.812 3.25l.4 1.75l3.421.428l.429 2.572l.25.75H3.25l.25-.75l.429-2.572L7.35 17.5l.4-1.75l.813-3.25zm-2.5 6h5");
}

:global(.b36niz7vv) {
  cx: 12px;
  cy: 7.75px;
  r: 2.25px;
}

:global(.u1w-djb2c) {
  d: path("M6.75 8a5.25 5.25 0 1 1 10.5 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
