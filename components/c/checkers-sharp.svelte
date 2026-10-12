<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="d8mt2_n-r"/><path class="vj_6e8bny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:checkers-sharp" {...props}></Icon>
<style>
:global(.d8mt2_n-r) {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.vj_6e8bny) {
  d: path("m9.67 13.26l-.34-2.27l-.08-.49l.38.32l.74.61l.38.32l.26-.42l.73-1.16l.26-.42l.26.42l.73 1.16l.26.42l.38-.32l.74-.61l.38-.32l-.08.49l-.34 2.27l-.08.49h-4.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
