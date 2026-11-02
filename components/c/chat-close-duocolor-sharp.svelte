<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b24i2e9uj"/><path class="kwh_pwbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-close-duocolor-sharp" {...props}></Icon>
<style>
:global(.b24i2e9uj) {
  stroke-opacity: 0.4;
  d: path("m10 8l4 4m0-4l-4 4");
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
