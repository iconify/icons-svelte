<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u9zbhwwpi"/><path class="er-rmmbme"/><path class="vrzeiketi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:invite-accept-outline-regular" {...props}></Icon>
<style>
:global(.er-rmmbme) {
  d: path("M6 10V5h6v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u9zbhwwpi) {
  d: path("M2 10v9h14v-9Z");
}

:global(.vrzeiketi) {
  d: path("m16 15 2 2 4 -4");
}

</style>
