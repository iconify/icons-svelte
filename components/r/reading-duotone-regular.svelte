<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k4cq6khhk"/><path class="qt8zkkbfu"/><path class="yzyen6bgh"/><path class="xhqu47btw"/><path class="t-0jg7bvk"/><path class="x4kxwubfs"/><path class="m0msdy1bm"/><path class="exo870qhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-duotone-regular" {...props}></Icon>
<style>
:global(.exo870qhz) {
  d: path("M15 11h4");
}

:global(.k4cq6khhk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m0msdy1bm) {
  d: path("M5 11h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qt8zkkbfu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t-0jg7bvk) {
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
}

:global(.x4kxwubfs) {
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
}

:global(.xhqu47btw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yzyen6bgh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
