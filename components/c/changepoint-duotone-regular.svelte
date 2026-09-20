<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o6iq34b2g"/><path class="r0jirgjze"/><path class="loqr5yt1s"/><path class="g-wxd1xvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:changepoint-duotone-regular" {...props}></Icon>
<style>
:global(.g-wxd1xvy) {
  d: path("M12 5v2.5");
}

:global(.loqr5yt1s) {
  d: path("M4 10h8l7 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o6iq34b2g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10h8l7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r0jirgjze) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
