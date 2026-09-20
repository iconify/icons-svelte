<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lxc0b_rlj"/><path class="ik8n3ab2d"/><path class="t4qf-ybkd"/><path class="odu-y8bfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-license-outline-regular" {...props}></Icon>
<style>
:global(.ik8n3ab2d) {
  d: path("m12 6.5 3.5 3.5 -3.5 3.5L8.5 10Z");
}

:global(.lxc0b_rlj) {
  d: path("M5 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.odu-y8bfl) {
  d: path("M14.5 17.5V21");
}

:global(.t4qf-ybkd) {
  d: path("M9.5 17.5V21");
}

</style>
