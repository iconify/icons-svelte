<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uhve_kb3h"/><path class="hzf9y-bdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:playing-cards-duocolor-sharp" {...props}></Icon>
<style>
:global(.hzf9y-bdg) {
  d: path("M4 7h12v14H4Zm4-4h12v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uhve_kb3h) {
  stroke-opacity: 0.4;
  d: path("m10 11l2 3l-2 3l-2-3Z");
}

</style>
