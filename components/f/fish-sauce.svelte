<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o5h5l2bri"/><path class="pi92fvbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fish-sauce" {...props}></Icon>
<style>
:global(.o5h5l2bri) {
  d: path("M9.5 2.5h5v3h-5Zm1 3v2l-4 3.5v8.5a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2V11l-4-3.5v-2");
}

:global(.pi92fvbwb) {
  d: path("M9 16c1.25-2 3.5-2 4.5 0l1.5-1.25v2.5L13.5 16c-1 2-3.25 2-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
