<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="h3oz9plut"/><path class="q6oi0ob4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:briefcase-arrow-down-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h3oz9plut) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 6L22 18C22 18.5523 21.5523 19 21 19L3 19C2.4477 19 2 18.5523 2 18L2 6C2 5.4477 2.4477 5 3 5L21 5C21.5523 5 22 5.4477 22 6ZM11 11.5858L9.4142 10L8 11.4142L11.2929 14.7071C11.4804 14.8946 11.7348 15 12 15C12.2652 15 12.5196 14.8946 12.7071 14.7071L16 11.4142L14.5858 10L13 11.5858L13 9L11 9L11 11.5858Z");
  stroke: none;
}

:global(.q6oi0ob4m) {
  d: path("M8.5 6L8.5 2L15.5 2L15.5 6M2 22L22 22");
}

</style>
