<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fr20hdeft"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:clinic-outline-regular" {...props}></Icon>
<style>
:global(.e8vupfb9c) {
  d: path("M9.5 14h5");
}

:global(.fr20hdeft) {
  d: path("M3 20v-8h5V7h8v5h5v8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ptaeireto) {
  d: path("M12 11.5v5");
}

</style>
