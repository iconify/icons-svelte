<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b0pkgbbgy"/><path class="c5kihbcac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:action-item" {...props}></Icon>
<style>
:global(.b0pkgbbgy) {
  d: path("M2.5 6.75H13v10.5H2.5ZM16 12h5.5");
}

:global(.c5kihbcac) {
  d: path("m5.25 12.25l2 2L10 10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
