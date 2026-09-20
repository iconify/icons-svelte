<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="l-z02yb4d"/><path class="rf0c3ccmk"/><path class="m6nkjhiin"/><path class="f6tzkgyet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:long-running-operation-outline-regular" {...props}></Icon>
<style>
:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.f6tzkgyet) {
  d: path("M12 16h2.5");
}

:global(.l-z02yb4d) {
  d: path("M11 5v5l2.5 -2.5Z");
}

:global(.m6nkjhiin) {
  d: path("M12 13v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rf0c3ccmk) {
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
