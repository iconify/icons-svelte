<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lppmt7bfa"/><path class="yl_sn5bpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-from-line-duocolor-round" {...props}></Icon>
<style>
:global(.lppmt7bfa) {
  stroke-opacity: 0.4;
  d: path("M20 6v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yl_sn5bpb) {
  d: path("m8 8l-4 4l4 4m-4-4h12");
}

</style>
