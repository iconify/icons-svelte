<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0i6v3psu"/><path class="ubbg1ibwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:genre-anime" {...props}></Icon>
<style>
:global(.ubbg1ibwc) {
  d: path("M6.25 12.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm6-1.5h.01M17 9.5l.5-2.5m1.25 3.75L20 8.5m.5 3.5l1.5-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0i6v3psu) {
  d: path("M2.5 13q9.5-9.5 19 0q-9.5 8.5-19 0Z");
}

</style>
