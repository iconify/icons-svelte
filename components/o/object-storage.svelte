<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="urirpovri"/><path class="k4iidbcyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:object-storage" {...props}></Icon>
<style>
:global(.k4iidbcyq) {
  d: path("M8 7h4v4H8Zm4 0h4v4h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.urirpovri) {
  d: path("M3.5 11h17l-2 10.5h-13Zm0 0a8.5 8.5 0 0 1 17 0");
}

</style>
