<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q_5l_3bgt"/><path class="gzza8wbrt"/><path class="s6i5bu6gd"/><path class="sqsxh9blm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mtu-outline-regular" {...props}></Icon>
<style>
:global(.gzza8wbrt) {
  d: path("M2 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q_5l_3bgt) {
  d: path("M5 10a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.s6i5bu6gd) {
  d: path("M22 5v14");
}

:global(.sqsxh9blm) {
  d: path("M5 5h14");
}

</style>
