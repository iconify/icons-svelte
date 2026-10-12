<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qcs3mtvaa"/><path class="kkcf6vbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dastarkhwan-sharp" {...props}></Icon>
<style>
:global(.kkcf6vbtz) {
  d: path("M6 12.5a2.75 1.5 0 1 0 5.5 0a2.75 1.5 0 1 0-5.5 0Zm6.5 0a2.75 1.5 0 1 0 5.5 0a2.75 1.5 0 1 0-5.5 0Zm-7 5.5v2.75m4-2.75v2.75m5-2.75v2.75m4-2.75v2.75");
}

:global(.qcs3mtvaa) {
  d: path("M7.5 6h10.25l.35 1.2l2.8 9.6l.35 1.2H2.75l.35-1.2l2.8-9.6l.35-1.2z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
