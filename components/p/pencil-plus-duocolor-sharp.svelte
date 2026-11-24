<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2x1j6b-n"/><path class="lojoc6byk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-plus-duocolor-sharp" {...props}></Icon>
<style>
:global(.lojoc6byk) {
  d: path("M6 20v-3L16 7l3 3L9 20zm8-11l3 3");
}

:global(.n2x1j6b-n) {
  stroke-opacity: 0.4;
  d: path("M4 7h6M7 4v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
