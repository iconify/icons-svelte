<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="auh81hbuq"/><path class="fax-h90di"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kaaba-sharp" {...props}></Icon>
<style>
:global(.auh81hbuq) {
  d: path("m12.7 3.02l7.85 2.96l.7.27V17.5l-.7.28l-7.85 3.19l-.7.28l-.7-.28l-7.85-3.19l-.7-.28V6.25l.7-.27l7.85-2.96l.7-.27z");
}

:global(.fax-h90di) {
  d: path("m3 6.5l9 3.5l9-3.5M12 10v11M3 10l9 3.5l9-3.5m-5.75 10v-3.25l2-.75v3.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
