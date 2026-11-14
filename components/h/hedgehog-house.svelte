<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eiq8altaq"/><path class="tsuydh_kj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hedgehog-house" {...props}></Icon>
<style>
:global(.eiq8altaq) {
  d: path("m4.5 9.5l7.5-7l7.5 7v7.75h-15Z");
}

:global(.tsuydh_kj) {
  d: path("M10 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7 9L5 20l2 1.5L9 20l2 1.5l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
