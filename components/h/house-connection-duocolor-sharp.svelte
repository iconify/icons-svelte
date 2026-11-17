<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="klsy0lb8n"/><path class="wxmc1yhhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-connection-duocolor-sharp" {...props}></Icon>
<style>
:global(.klsy0lb8n) {
  stroke-opacity: 0.4;
  d: path("M12 17v4m-8 0h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wxmc1yhhu) {
  d: path("m12 3l6.222 5.444V17H5.778V8.444z");
}

</style>
