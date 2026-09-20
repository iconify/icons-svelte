<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iymet_cml"/><path class="hpmnlabtt"/><path class="ldhdatnvd"/><path class="b9ex0_kla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:llm-outline-regular" {...props}></Icon>
<style>
:global(.b9ex0_kla) {
  d: path("M6 16h6");
}

:global(.hpmnlabtt) {
  d: path("M6 9h12");
}

:global(.iymet_cml) {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

:global(.ldhdatnvd) {
  d: path("M6 12.5h9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
