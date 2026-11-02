<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cq75u6x-g"/><path class="h8uaxgswm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-duocolor-sharp" {...props}></Icon>
<style>
:global(.cq75u6x-g) {
  stroke-opacity: 0.4;
  d: path("m4 8l2-4h12l2 4M4 8h16");
}

:global(.h8uaxgswm) {
  d: path("M4 8v12h16V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
