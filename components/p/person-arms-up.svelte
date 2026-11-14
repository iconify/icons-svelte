<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nscw-c0yc"/><path class="g-t4v1n-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:person-arms-up" {...props}></Icon>
<style>
:global(.g-t4v1n-a) {
  d: path("m5.5 3.5l3 5.5h7l3-5.5");
}

:global(.nscw-c0yc) {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4v6m-3 6l3-6l3 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
