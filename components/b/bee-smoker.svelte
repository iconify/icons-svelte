<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uavispb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bee-smoker" {...props}></Icon>
<style>
:global(.uavispb3h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9.5l2-3h3l2 3V20a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 9.5 20Zm3.5-3v-2L16 3M4.5 12.75l-.777.486a1.5 1.5 0 0 0-.508 2.016L4.5 17.5a1.071 1.071 0 0 0 2-.531v-3.111a1.307 1.307 0 0 0-2-1.108m2 2.25h3m0-5.5h7M18.75 6c2.75-1-.25-3 2.5-4");
}

</style>
