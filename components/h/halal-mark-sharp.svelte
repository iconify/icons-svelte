<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f5tv6d3gk"/><path class="ob_faobej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:halal-mark-sharp" {...props}></Icon>
<style>
:global(.f5tv6d3gk) {
  d: path("m12.64 3.14l.85.51l.65.38l.75-.01l.99-.02l.75-.01l.36.65l.48.87l.36.66l.66.36l.87.48l.65.37l-.01.74l-.02.99l-.01.75l.38.65l.51.85l.39.64l-.39.64l-.51.85l-.38.65l.01.75l.02.99l.01.75l-.65.36l-.87.48l-.66.36l-.36.66l-.48.87l-.36.65l-.75-.01l-.99-.02l-.75-.01l-.65.38l-.85.51l-.64.39l-.64-.39l-.85-.51l-.65-.38l-.75.01l-.99.02l-.74.01l-.37-.65l-.48-.87l-.36-.66l-.66-.36l-.87-.48l-.65-.36l.01-.75l.02-.99l.01-.75l-.38-.65l-.51-.85l-.39-.64l.39-.64l.51-.85l.38-.65l-.01-.75L4 8.12l-.01-.75l.65-.36l.87-.48l.66-.36l.36-.66l.48-.87l.36-.65l.75.01l.99.02l.75.01l.65-.38l.85-.51l.64-.39z");
}

:global(.ob_faobej) {
  d: path("M14.5 8.25a4.5 4.5 0 1 0 0 7.5a4 4 0 0 1 0-7.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
