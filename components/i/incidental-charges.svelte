<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="myx7qnt-b"/><path class="nzw_hdb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:incidental-charges" {...props}></Icon>
<style>
:global(.myx7qnt-b) {
  d: path("M17.25 7h2.5a1 1 0 0 1 1 1v13.5l-2-1.5l-2 1.5l-2-1.5l-2 1.5l-2-1.5v-6.5");
}

:global(.nzw_hdb-o) {
  d: path("M3.25 4h14v9.5h-14Zm10.5 12.75h4M3.25 7.5h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
