<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngtiubbgl"/><path class="myadcub7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-edit-duocolor-sharp" {...props}></Icon>
<style>
:global(.myadcub7g) {
  d: path("M11 4H4v16h16v-7");
}

:global(.ngtiubbgl) {
  stroke-opacity: 0.4;
  d: path("M9 15v-3l9-9l3 3l-9 9Zm6-9l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
