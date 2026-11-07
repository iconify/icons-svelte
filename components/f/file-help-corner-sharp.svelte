<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0o06xb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-help-corner-sharp" {...props}></Icon>
<style>
:global(.k0o06xb8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-4 7a2 2 0 1 1 2 2m0 3h.01");
}

</style>
