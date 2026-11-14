<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="seyrijbbk"/><path class="se82k7w0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contact-book" {...props}></Icon>
<style>
:global(.se82k7w0r) {
  d: path("M11.75 9.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM11 17c0-1.6 1.3-2.75 3-2.75s3 1.15 3 2.75");
}

:global(.seyrijbbk) {
  d: path("M4 2.5h16v19H4Zm4 0v19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
