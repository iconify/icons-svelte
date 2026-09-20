<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aj1uncbqw"/><path class="pj7ux4r4p"/><path class="c7k5qsbpo"/><path class="fn7sp80dx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:carer-outline-regular" {...props}></Icon>
<style>
:global(.aj1uncbqw) {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.c7k5qsbpo) {
  d: path("M2 21v-3a5 5 0 0 1 10 0");
}

:global(.fn7sp80dx) {
  d: path("M12 21v-4a4 4 0 0 1 8 0v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pj7ux4r4p) {
  d: path("M15 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
