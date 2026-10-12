<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o-8i64mep"/><path class="gc614nxdp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:prescription-pad-sharp" {...props}></Icon>
<style>
:global(.gc614nxdp) {
  d: path("M19.75 6.75v14.5H6.25m-3-18.5H16.5v2.5H3.25zm4.75 11V8h3.4v3H8m1.75 0l3 3m0-2.75L10 14m-2 2.25h6.5");
}

:global(.o-8i64mep) {
  d: path("M3.25 5.25H16.5v13.5H3.25z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
