<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i66ibbo0w"/><path class="yrsxudblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-left-up-sharp" {...props}></Icon>
<style>
:global(.i66ibbo0w) {
  d: path("M19.75 19.75H9.25v-15");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yrsxudblh) {
  d: path("M13 8.5L9.25 4.75L5.5 8.5");
}

</style>
