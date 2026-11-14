<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a77g8oisl"/><path class="r_5ej1lys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lock-small" {...props}></Icon>
<style>
:global(.a77g8oisl) {
  fill: currentColor;
  d: path("M6.5 11h11v9h-11Z");
}

:global(.r_5ej1lys) {
  d: path("M9 11V7a3 3 0 0 1 6 0v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
