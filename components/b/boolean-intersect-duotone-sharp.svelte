<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iekwx9bzu"/><path class="b7eiz6b0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:boolean-intersect-duotone-sharp" {...props}></Icon>
<style>
:global(.b7eiz6b0p) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9h6v6H9ZM3 7V3h4m4 0h4v2M3 11v4h2m14-6h2v4m0 4v4h-4m-8-2v2h4");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iekwx9bzu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 15V9a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

</style>
