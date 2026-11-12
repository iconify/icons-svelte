<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_vs41dqo"/><path class="ocmla0jdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:boolean-intersect-duocolor-sharp" {...props}></Icon>
<style>
:global(.n_vs41dqo) {
  stroke-opacity: 0.4;
  d: path("M3 7V3h4m4 0h4v2M3 11v4h2m14-6h2v4m0 4v4h-4m-8-2v2h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ocmla0jdf) {
  d: path("M9 9h6v6H9Z");
}

</style>
