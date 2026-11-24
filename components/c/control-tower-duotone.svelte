<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t44_ks3ir"/><path class="ox-b17b7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:control-tower-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ox-b17b7a) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 13H7l-2-3c-.855-1.282-.855-3 0-3h14c.855 0 .855 1.718 0 3zm-8 0v8m6-8v8M3 21h18M12 7V3M8 7l2 6m6-6l-2 6");
}

:global(.t44_ks3ir) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 13h-2v8H9v-8H7l-2-3c-.855-1.282-.855-3 0-3h14c.855 0 .855 1.718 0 3Z");
}

</style>
