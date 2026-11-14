<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xcmjvmbet"/><path class="c9k2ngkio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:exit-door-sign" {...props}></Icon>
<style>
:global(.c9k2ngkio) {
  d: path("M4 2.5L10 5v14l-6 2.5Zm9 9.5h8m-3.5-3.5L21 12l-3.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xcmjvmbet) {
  d: path("M14 7.5v-5H4v19h10v-5");
}

</style>
