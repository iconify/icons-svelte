<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wrw2kc1sb"/><path class="mwue9wb_t"/><path class="pzovgl99o"/><path class="q5w-xob0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reply-duotone-regular" {...props}></Icon>
<style>
:global(.mwue9wb_t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzovgl99o) {
  d: path("M8 4 3 9l5 5");
}

:global(.q5w-xob0a) {
  d: path("M3 9h14v11");
}

:global(.wrw2kc1sb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4 3 9l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
