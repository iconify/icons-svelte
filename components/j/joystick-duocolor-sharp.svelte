<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jb3ap4bhw"/><path class="u28jvld6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:joystick-duocolor-sharp" {...props}></Icon>
<style>
:global(.jb3ap4bhw) {
  stroke-opacity: 0.4;
  d: path("M12 15V9M9 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u28jvld6q) {
  d: path("M3 15h18v6H3Zm4 0v-2");
}

</style>
