<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ao_ai8bks"/><path class="t490cnlbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:filter-off-duotone-sharp" {...props}></Icon>
<style>
:global(.ao_ai8bks) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14 18l-4 2v-8L4 6V4h2l8 8ZM12 4h8v2l-3 3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.t490cnlbq) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h8v2l-3 3m-3 3v6l-4 2v-8L4 6V4h2M4 2l14 14");
}

</style>
