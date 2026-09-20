<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iczafxbjt"/><path class="k-56v1mby"/><path class="fjv9jkqys"/><path class="zy0aipbok"/><path class="h2-2dgnfu"/><path class="sm02sv71h"/><path class="gtujb54ma"/><path class="g_k4zfu5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-duotone-regular" {...props}></Icon>
<style>
:global(.fjv9jkqys) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g_k4zfu5d) {
  d: path("M14 15h6");
}

:global(.gtujb54ma) {
  d: path("M4 9h6");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.iczafxbjt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-56v1mby) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.zy0aipbok) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
