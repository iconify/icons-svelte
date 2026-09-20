<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h2-2dgnfu"/><path class="sm02sv71h"/><path class="gtujb54ma"/><path class="g_k4zfu5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-outline-regular" {...props}></Icon>
<style>
:global(.g_k4zfu5d) {
  d: path("M14 15h6");
}

:global(.gtujb54ma) {
  d: path("M4 9h6");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sm02sv71h) {
  d: path("M7 6v6");
}

</style>
