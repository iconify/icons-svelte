<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="m7ac2s0vc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:patient-id-card" {...props}></Icon>
<style>
:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.m7ac2s0vc) {
  d: path("M6.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 6c.5-2 2-3 3.5-3s3 1 3.5 3m2.5-6.5H19m-4.5 4H18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
