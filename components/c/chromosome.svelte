<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ss_k9nbrc"/><path class="sh2e90bun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chromosome" {...props}></Icon>
<style>
:global(.sh2e90bun) {
  d: path("M16.5 3.5c-1.5 5.5-3 7-4.5 8.5s-3 3-4.5 8.5");
}

:global(.ss_k9nbrc) {
  d: path("M7.5 3.5c1.5 5.5 3 7 4.5 8.5s3 3 4.5 8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
