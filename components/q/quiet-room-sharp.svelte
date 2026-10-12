<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dc1vmo-aa"/><path class="fqv97q5un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quiet-room-sharp" {...props}></Icon>
<style>
:global(.dc1vmo-aa) {
  d: path("M4.75 21.25V2.75h14.5v18.5m-16.5 0h18.5");
}

:global(.fqv97q5un) {
  d: path("M13.5 7.5a4 4 0 1 0 2.75 6.25A5 5 0 0 1 13.5 7.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
