<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rzeu6nb4c"/><circle class="o-6fcb5pr"/><path class="q2ijv29-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crop-rows-sharp" {...props}></Icon>
<style>
:global(.o-6fcb5pr) {
  cx: 16.5px;
  cy: 5px;
  r: 2.25px;
}

:global(.q2ijv29-k) {
  d: path("M2.75 10.25h3.5m11.5 0h3.5");
}

:global(.rzeu6nb4c) {
  d: path("m3.09 20.53l4.57-9.56l.34-.72h8l.34.72l4.57 9.56l.34.72H2.75zm4.66.72L9.55 14M12 21.25V14m4.25 7.25L14.45 14");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
