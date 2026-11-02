<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkt9pecra"/><path class="x9herjs3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:group-duocolor-sharp" {...props}></Icon>
<style>
:global(.lkt9pecra) {
  stroke-opacity: 0.4;
  d: path("M3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x9herjs3p) {
  d: path("M7 7h7v5H7zm3 5h7v5h-7z");
}

</style>
