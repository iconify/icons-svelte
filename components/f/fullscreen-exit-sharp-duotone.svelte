<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zakzfrb_i"/><path class="sgr6ct_qp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-exit-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sgr6ct_qp) {
  d: path("M2 14L10 14L10 22M9.8243 14.1757L2.7071 21.2929");
}

:global(.zakzfrb_i) {
  stroke-opacity: 0.4;
  d: path("M22 10L14 10L14 2M14.1757 9.8243L21.2929 2.7071");
}

</style>
