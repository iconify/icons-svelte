<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qlnlfob5e"/><path class="ogbtfdbcm"/><path class="vnrefqbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crm" {...props}></Icon>
<style>
:global(.ogbtfdbcm) {
  d: path("M5.5 10V8.5A1.5 1.5 0 0 1 7 7h10a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 17 17h-1.5");
}

:global(.qlnlfob5e) {
  d: path("M2.5 10h13v10h-13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vnrefqbky) {
  d: path("M8.5 7V5.5A1.5 1.5 0 0 1 10 4h10a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 20 14h-1.5m-13 1h5");
}

</style>
