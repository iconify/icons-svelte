<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gqkur2bfu"/><path class="u2lgn4tdl"/><path class="v_agw5__m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rock-garden" {...props}></Icon>
<style>
:global(.gqkur2bfu) {
  d: path("M4 17a8 3 0 1 0 16 0a8 3 0 1 0-16 0Z");
}

:global(.u2lgn4tdl) {
  d: path("M6.5 11.5a5.5 2.5 0 1 0 11 0a5.5 2.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_agw5__m) {
  d: path("M8.25 6.75a3.75 2.25 0 1 0 7.5 0a3.75 2.25 0 1 0-7.5 0Z");
}

</style>
