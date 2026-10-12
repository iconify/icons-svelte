<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zlhvtw3uf"/><path class="haz4ihblf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fuse-sharp" {...props}></Icon>
<style>
:global(.haz4ihblf) {
  d: path("M8.75 12L10 10l2 4l2-4l1.25 2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zlhvtw3uf) {
  d: path("M2.75 5.75v12.5m18.5-12.5v12.5M5.75 7h12.5v10H5.75z");
}

</style>
