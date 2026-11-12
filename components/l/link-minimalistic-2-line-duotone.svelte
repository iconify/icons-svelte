<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pi6xz2b_n"/><path class="dtoolxbmj"/><path class="nvxxmxb7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-2-line-duotone" {...props}></Icon>
<style>
:global(.dtoolxbmj) {
  d: path("M9.83789 14.1625L14.163 9.8374");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nvxxmxb7r) {
  d: path("M9.83789 5.51236L10.5587 4.79151C12.9474 2.40283 16.8202 2.40283 19.2089 4.79151C21.5976 7.18019 21.5976 11.053 19.2089 13.4417L18.4881 14.1625");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.pi6xz2b_n) {
  d: path("M14.1625 18.4876L13.4417 19.2085C11.053 21.5972 7.18019 21.5972 4.79151 19.2085C2.40283 16.8198 2.40283 12.947 4.79151 10.5583L5.51236 9.83746");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
