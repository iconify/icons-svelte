<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e11ww-b5e"/><path class="mcsf4ok4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:home-intercom" {...props}></Icon>
<style>
:global(.e11ww-b5e) {
  d: path("M15 20v1.5H3v-19h12V13m0 2.4v2.2");
}

:global(.mcsf4ok4f) {
  d: path("M5.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm2 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm10.25-2.25a3.25 3.25 0 0 1 0 4.5m2-6.5a6 6 0 0 1 0 8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
