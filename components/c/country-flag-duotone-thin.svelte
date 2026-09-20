<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pv3mbccsc"/><path class="ftcyjfb1t"/><path class="t1dvawbqd"/><path class="a_-94rbje"/><path class="f9uxp9ptq"/><path class="he6k4tqrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:country-flag-duotone-thin" {...props}></Icon>
<style>
:global(.a_-94rbje) {
  d: path("M5 2v20");
}

:global(.f9uxp9ptq) {
  d: path("M5 4h14v9H5");
}

:global(.ftcyjfb1t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4h14v9H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.he6k4tqrw) {
  d: path("M5 8.5h14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pv3mbccsc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1dvawbqd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8.5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
