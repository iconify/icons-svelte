<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="m22ncdb-i"/><path class="f3-7m-bxu"/><path class="y-b7bp8ez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fitbod" {...props}></Icon>
<style>
:global(.f3-7m-bxu) {
  d: path("m16.066 13.87l1.052-1.8l13.835.04l6.883 11.93l-6.954 11.89l-13.835-.04l-6.883-11.93l3.087-5.279m17.702-6.571l3.35-5.76");
}

:global(.m22ncdb-i) {
  d: path("M44.5 24.06L34.197 41.71l-20.5-.06L3.5 23.94L13.803 6.29l20.5.06zm-41-.12l6.664.02");
}

:global(.y-b7bp8ez) {
  d: path("M13.251 18.68h10.057l2.77-4.811H16.067");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
