<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ewkyndb4w"/><path class="w3is48jcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bank-queue-display" {...props}></Icon>
<style>
:global(.ewkyndb4w) {
  d: path("M2.5 5.5h19v13h-19Zm3 0L9 2m9.5 3.5L15 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w3is48jcu) {
  d: path("m5.75 15l2-6.5l2 6.5M6.5 12.75H9m4.25-4.25H18L15 15");
}

</style>
