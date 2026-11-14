<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="smbpj8b0b"/><path class="xp1_wt6oq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:guest-arrival-time" {...props}></Icon>
<style>
:global(.smbpj8b0b) {
  d: path("M5.5 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0ZM3 21l4.75-4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xp1_wt6oq) {
  d: path("M4.25 16.25h3.5v3.5M13.5 6v4.5l3 2");
}

</style>
