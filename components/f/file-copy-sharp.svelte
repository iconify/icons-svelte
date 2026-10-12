<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uycia5ppg"/><path class="xnph3kdsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-copy-sharp" {...props}></Icon>
<style>
:global(.uycia5ppg) {
  d: path("M15.25 5.75h-8v15.5h13.5v-11Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xnph3kdsl) {
  d: path("M4.25 15.75v-13h8.5m1.5 9.5v5m-2.5-2.5h5");
}

</style>
