<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_buvbbmu"/><path class="ext23b30v"/><path class="g6xh1ob7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-puller" {...props}></Icon>
<style>
:global(.e_buvbbmu) {
  d: path("M4 8a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 4 8Z");
}

:global(.ext23b30v) {
  d: path("M9.5 2.5H19V17a2.5 2.5 0 0 1-5 0v-1.5");
}

:global(.g6xh1ob7e) {
  d: path("M7.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
