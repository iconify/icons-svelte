<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t_lzl-bvc"/><path class="dssi4fbls"/><path class="c3wgojkty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-vet" {...props}></Icon>
<style>
:global(.c3wgojkty) {
  d: path("M18 15v6m-3-3h6");
}

:global(.dssi4fbls) {
  fill: currentColor;
  d: path("M2 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM15 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.t_lzl-bvc) {
  d: path("M12.194 18.651A6.8 6.8 0 0 1 10 19c-3 0-5-1.75-5-3.5S7.25 12 10 12c2.609 0 4.768 1.575 4.982 3.231");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
