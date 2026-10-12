<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ake-zzb7h"/><path class="pe4pc-o8q"/><circle class="i25ptdbyc"/><path class="wxuf-2f2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:key-exchange-sharp" {...props}></Icon>
<style>
:global(.ake-zzb7h) {
  cx: 5.5px;
  cy: 6px;
  r: 2.75px;
}

:global(.i25ptdbyc) {
  cx: 18.5px;
  cy: 18px;
  r: 2.75px;
}

:global(.pe4pc-o8q) {
  d: path("M8.25 6H15m-2 0v2m6.25-4.5v5.75M17.5 7.5l1.75 1.75L21 7.5");
}

:global(.wxuf-2f2u) {
  d: path("M15.75 18H9m2 0v-2m-6.25 4.5v-5.75M3 16.5l1.75-1.75L6.5 16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
