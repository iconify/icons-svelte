<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ad36pfl1z"/><path class="lj4d6jb7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ferry-disembark" {...props}></Icon>
<style>
:global(.ad36pfl1z) {
  d: path("M2.5 12H14l-1.5 4.5H4Zm2-5.5h7V12h-7ZM17.25 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.lj4d6jb7h) {
  d: path("M18.75 7.75L17.5 13.5l-2 6m2-6l2.5 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
