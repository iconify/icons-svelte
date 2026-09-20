<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m6u_t4bqm"/><path class="y5jslcbiw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-open-outline-regular" {...props}></Icon>
<style>
:global(.m6u_t4bqm) {
  d: path("M4 20V4h5l3 3h7v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y5jslcbiw) {
  d: path("m4 20 8 -8h10l-8 8Z");
}

</style>
