<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d85_p7ook"/><path class="y5eq5wale"/><path class="m_wupbc4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-interpreter-outline-regular" {...props}></Icon>
<style>
:global(.d85_p7ook) {
  d: path("m7 7 -5 5 5 5");
}

:global(.m_wupbc4b) {
  d: path("m17 7 5 5 -5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y5eq5wale) {
  d: path("M10 9v6l3 -3Z");
}

</style>
