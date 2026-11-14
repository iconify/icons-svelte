<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ejxb6jo-u"/><path class="mhcn6xnzt"/><path class="nz8ckabir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:assisted-living" {...props}></Icon>
<style>
:global(.ejxb6jo-u) {
  d: path("m12.5 21.5l.75-11h6.5l.75 11M2.5 6.75l4.75-4l4.75 4");
}

:global(.mhcn6xnzt) {
  d: path("M3.75 5.75v5.75c0 .75.5 1.25 1.25 1.25h4.75c.5 0 1.25-.5 1.25-1.25V5.75m2 9.75h7m-8.25-5h1.5m6.5 0h1.5");
}

:global(.nz8ckabir) {
  fill: currentColor;
  d: path("M11.75 21a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm8 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
