<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zn6298aab"/><path class="kyrdb7bzq"/><path class="pghnb4t3q"/><path class="amhmhobty"/><path class="i5d2grbwo"/><path class="s27ukbqxc"/><path class="jls6b8fnh"/><path class="l9kfpmzgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corpus-add-duotone-thin" {...props}></Icon>
<style>
:global(.amhmhobty) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5d2grbwo) {
  d: path("M13 2H6v14h10V5");
}

:global(.jls6b8fnh) {
  d: path("M16.5 4.5h5");
}

:global(.kyrdb7bzq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8H9v14h10V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l9kfpmzgx) {
  d: path("M19 2v5");
}

:global(.pghnb4t3q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 4.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s27ukbqxc) {
  d: path("M16 8H9v14h10V11");
}

:global(.zn6298aab) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 2H6v14h10V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
