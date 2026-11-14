<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g61hjg93y"/><path class="unthf8b2b"/><path class="d_b-5-bll"/><path class="m2um35nxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ecg-electrodes" {...props}></Icon>
<style>
:global(.d_b-5-bll) {
  fill: currentColor;
  d: path("M8 13.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.g61hjg93y) {
  d: path("M2.25 13.5a7.25 7.25 0 1 0 14.5 0a7.25 7.25 0 1 0-14.5 0Z");
}

:global(.m2um35nxv) {
  d: path("M9.5 12c0-5.5 2.5-9 6.5-9h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unthf8b2b) {
  d: path("M5.5 13.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
