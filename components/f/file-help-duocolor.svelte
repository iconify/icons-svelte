<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="itiaosczt"/><path class="qvcpzubvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-help-duocolor" {...props}></Icon>
<style>
:global(.itiaosczt) {
  stroke-opacity: 0.4;
  d: path("M9 13a2 2 0 1 1 2 2m0 3h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvcpzubvw) {
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

</style>
