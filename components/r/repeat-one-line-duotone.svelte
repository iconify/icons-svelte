<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1afujhin"/><path class="sec9xqbsa"/><path class="vny47hble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sec9xqbsa) {
  d: path("M15 21L13 19H15C18.866 19 22 15.866 22 12C22 8.13401 18.866 5 15 5H14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.t1afujhin) {
  d: path("M9.5 19H9.00028C5.13428 19 2 15.866 2 12C2 8.13401 5.13401 5 9 5H11L9 3");
}

:global(.vny47hble) {
  d: path("M10.5 11.5L12 10V14");
}

</style>
