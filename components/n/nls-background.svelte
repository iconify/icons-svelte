<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gf5awhzyq"/><path clip-rule="evenodd" class="sldlgv7ec"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:nls-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gf5awhzyq) {
  fill: var(--svg-color--ff562d, #ff562d);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sldlgv7ec) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-15.998A8 8 0 0 0 12 20M9.31 8A1.31 1.31 0 0 0 8 9.31v5.38A1.31 1.31 0 0 0 9.31 16h5.38A1.31 1.31 0 0 0 16 14.69V9.31A1.31 1.31 0 0 0 14.69 8z");
}

</style>
