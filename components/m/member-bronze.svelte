<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvkw6zboz"/><path class="nkv77ywgc"/><path class="btp282b5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:member-bronze" {...props}></Icon>
<style>
:global(.btp282b5z) {
  d: path("M9.25 16.5L12 13.75l2.75 2.75");
}

:global(.nkv77ywgc) {
  d: path("M5.75 15a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Z");
}

:global(.pvkw6zboz) {
  d: path("M6.5 2.5H10L12 6l2-3.5h3.5l-3 6.5h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
