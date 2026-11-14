<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn_c5lflo"/><path class="h8hbdqbky"/><path class="xemh9nb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ball-head" {...props}></Icon>
<style>
:global(.h8hbdqbky) {
  d: path("M6.5 11a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xemh9nb-o) {
  d: path("M10.25 16.25v5.25h3.5v-5.25");
}

:global(.zn_c5lflo) {
  d: path("M5 2.5h14v3H5Z");
}

</style>
