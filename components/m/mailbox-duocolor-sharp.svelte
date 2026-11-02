<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ld8hjv5zq"/><path class="yxkxzw26j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mailbox-duocolor-sharp" {...props}></Icon>
<style>
:global(.ld8hjv5zq) {
  stroke-opacity: 0.4;
  d: path("M17 9V3h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yxkxzw26j) {
  d: path("M7 9h14v12H3v-8a4 4 0 0 1 4-4m0 0a4 4 0 0 1 4 4v8");
}

</style>
