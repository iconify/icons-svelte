<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw099db1h"/><path class="w39ko6tkz"/><path class="r7xk8o29f"/><path class="caznxbcdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-duotone-regular" {...props}></Icon>
<style>
:global(.caznxbcdb) {
  d: path("m7 9 5 -5 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.uw099db1h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w39ko6tkz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
