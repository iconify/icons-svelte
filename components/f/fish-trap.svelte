<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ya_svtbtz"/><path class="tpaqxzb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fish-trap" {...props}></Icon>
<style>
:global(.tpaqxzb4z) {
  d: path("M17.5 11c-1.5-2.5-5-2.5-6.5 0c1.5 2.5 5 2.5 6.5 0ZM11 11L9.5 9.5M11 11l-1.5 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ya_svtbtz) {
  d: path("M3 20.5v-8a9 9 0 0 1 18 0v8Zm0-8l5 2m-5 6l5-3.25");
}

</style>
