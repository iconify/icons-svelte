<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwv5ytb5v"/><path class="jqxjeebqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:filter-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.jqxjeebqx) {
  d: path("M12 4h8v2l-3 3m-3 3v6l-4 2v-8L4 6V4h2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rwv5ytb5v) {
  stroke-opacity: 0.4;
  d: path("m4 2l14 14");
}

</style>
