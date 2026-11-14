<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="us8_9rb8k"/><path class="ixv163bsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:apartment" {...props}></Icon>
<style>
:global(.ixv163bsh) {
  d: path("M10 21v-4h4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.us8_9rb8k) {
  d: path("M6 3h12v18H6Zm3.5 4.5h1m3 0h1m-5 4h1m3 0h1");
}

</style>
