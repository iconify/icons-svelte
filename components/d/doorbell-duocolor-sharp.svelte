<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v_s_3kbpt"/><path class="wwxprpzpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:doorbell-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v_s_3kbpt) {
  stroke-opacity: 0.4;
  d: path("M10 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.wwxprpzpe) {
  d: path("M6 3h12v18H6Zm4 5h4");
}

</style>
