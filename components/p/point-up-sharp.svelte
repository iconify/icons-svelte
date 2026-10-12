<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nkte53v-k"/><path class="t425h_b9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:point-up-sharp" {...props}></Icon>
<style>
:global(.nkte53v-k) {
  d: path("M10 12V3h2.5v7h4.25v6a5.25 5.25 0 0 1-5.25 5.25h-5V12h2Zm2.5-1.5v3");
}

:global(.t425h_b9i) {
  d: path("m7 15.5l2.8-.8l2.45 1.05");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
