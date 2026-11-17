<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wdkmecclg"/><path class="j3xrkxb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fence-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.j3xrkxb7y) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 21V7l1.553-3.106a.5.5 0 0 1 .894 0L9 7v14zm10 0V7l1.553-3.106a.5.5 0 0 1 .894 0L19 7v14zM3 10h2m4 0h6m4 0h2M3 16h2m4 0h6m4 0h2");
}

:global(.wdkmecclg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21V7l1.553-3.106a.5.5 0 0 1 .894 0L9 7v14Zm10 0V7l1.553-3.106a.5.5 0 0 1 .894 0L19 7v14Z");
}

</style>
