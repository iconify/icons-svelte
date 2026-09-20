<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h090oacoe"/><path class="t5xz5pb7f"/><path class="hpmnlabtt"/><path class="qyha_vbqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kite-duotone-regular" {...props}></Icon>
<style>
:global(.h090oacoe) {
  fill: currentColor;
  d: path("m12 3 6 6 -6 6 -6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hpmnlabtt) {
  d: path("M6 9h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qyha_vbqa) {
  d: path("M12 15c2 2 -2 3 0 6");
}

:global(.t5xz5pb7f) {
  d: path("m12 3 6 6 -6 6 -6 -6Z");
}

</style>
