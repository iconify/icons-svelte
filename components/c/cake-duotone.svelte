<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mkq95_fnn"/><path class="i7ww04bcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cake-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i7ww04bcl) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21v-8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8M3 21h18M4 16s.5-1 2-1s2.5 2 4 2s2.5-2 4-2s2.5 2 4 2s2-1 2-1M8 8v3m4-3v3m4-3v3M8 4h.01M12 4h.01M16 4h.01");
}

:global(.mkq95_fnn) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 22a1 1 0 0 1-1-1v-8a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v8a1 1 0 0 1-1 1Z");
}

</style>
