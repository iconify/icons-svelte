<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzsz_zb3m"/><path class="vz2irlb-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heart-valve" {...props}></Icon>
<style>
:global(.bzsz_zb3m) {
  d: path("M12 20S3 14.5 3 8.75C3 6.1 5.1 4 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75C21 14.5 12 20 12 20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vz2irlb-g) {
  d: path("M8.5 7.75c1.5.5 2.75 1.5 3.5 3m3.5-3c-1.5.5-2.75 1.5-3.5 3m0 1.75v3.75m-1.75-1.75L12 16.25l1.75-1.75");
}

</style>
