<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t4cd75htm"/><path class="bl8yslzdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-play-three-quarter-duotone" {...props}></Icon>
<style>
:global(.bl8yslzdk) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.592 3.11a9 9 0 1 1-7.481 7.482M4.719 6.71a9 9 0 0 1 1.99-1.991M10 9v6c0 .23.54.23 1 0l4-2a1.118 1.118 0 0 0 0-2l-4-2c-.46-.23-1-.23-1 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.t4cd75htm) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 9c0-.23.541-.23 1 0l4 2a1.118 1.118 0 0 1 0 2l-4 2c-.459.23-1 .23-1 0Z");
}

</style>
