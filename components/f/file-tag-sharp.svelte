<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z2li5jbjy"/><path class="sbhs3jbrg"/><path class="g1kxs5bwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-tag-sharp" {...props}></Icon>
<style>
:global(.g1kxs5bwq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 16.25h.01");
}

:global(.sbhs3jbrg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5m-11 4h4m2.75 2h2.5l.53.53l2.44 2.44l.53.53l-.53.53l-2.19 2.19l-.53.53l-.53-.53l-2.44-2.44l-.53-.53v-3.25z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.z2li5jbjy) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

</style>
