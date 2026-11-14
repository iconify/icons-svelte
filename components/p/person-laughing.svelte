<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qeoyudbox"/><path class="uf4px-5wz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:person-laughing" {...props}></Icon>
<style>
:global(.qeoyudbox) {
  d: path("M6 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm-2.5 13c0-2.5 3.5-4.25 8.5-4.25s8.5 1.75 8.5 4.25");
}

:global(.uf4px-5wz) {
  d: path("m8.75 7l1-1.25l1 1.25m2.5 0l1-1.25l1 1.25m-5.5 2.75h4.5a2.25 2.25 0 0 1-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
