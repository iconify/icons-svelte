<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fpf2snbwg"/><path class="hfr86bw5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mute-toggle-sharp" {...props}></Icon>
<style>
:global(.fpf2snbwg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25V9h3l3.5-3l1.23-1.101l.02 1.651v10.9l-.02 1.651L9.25 18l-3.5-3h-3v-1.25ZM13 9h8.25v6H13z");
}

:global(.hfr86bw5l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
