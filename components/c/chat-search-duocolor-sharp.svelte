<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hap96braw"/><path class="kwh_pwbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-search-duocolor-sharp" {...props}></Icon>
<style>
:global(.hap96braw) {
  stroke-opacity: 0.4;
  d: path("M9 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

:global(.kwh_pwbjw) {
  d: path("M12 17H7l-4 4V3h18v14z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
