<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f-sxzbb-h"/><path class="wc-s0rnob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:creator-badge-sharp" {...props}></Icon>
<style>
:global(.f-sxzbb-h) {
  d: path("m14.16 3.65l3.99 2.3l2.16 1.25v9.6l-2.16 1.25l-3.99 2.3L12 21.6l-2.16-1.25l-3.99-2.3l-2.16-1.25V7.2l2.16-1.25l3.99-2.3L12 2.4z");
}

:global(.wc-s0rnob) {
  d: path("M10.25 9.15v5.7l-.029 1.394L11.4 15.5l4.5-2.85l1.129-.65l-1.129-.65l-4.5-2.85l-1.179-.744z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
