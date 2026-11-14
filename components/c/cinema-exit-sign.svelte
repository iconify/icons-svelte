<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h2d817bxi"/><path class="s1thihbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cinema-exit-sign" {...props}></Icon>
<style>
:global(.h2d817bxi) {
  d: path("M2.5 6h19v12h-19ZM7 12h9.5");
}

:global(.s1thihbdu) {
  d: path("M13.25 8.75L16.5 12l-3.25 3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
