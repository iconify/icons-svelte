<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="odthcbc3j"/><path class="w6y9xrylg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jam-jar-sharp" {...props}></Icon>
<style>
:global(.odthcbc3j) {
  d: path("M5.25 3h13.5v4H5.25zM6 10h12v11.25H6V18.5Z");
}

:global(.w6y9xrylg) {
  d: path("M9.5 15.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
