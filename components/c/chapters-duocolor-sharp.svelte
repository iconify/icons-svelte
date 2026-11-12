<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="igvmqocwj"/><path class="evpjv6bed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chapters-duocolor-sharp" {...props}></Icon>
<style>
:global(.evpjv6bed) {
  d: path("M3 3h18v14H3Zm0 18h3m4 0h4m4 0h3");
}

:global(.igvmqocwj) {
  stroke-opacity: 0.4;
  d: path("m10 6l6 4l-6 4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
