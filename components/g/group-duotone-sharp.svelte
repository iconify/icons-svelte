<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ei2ayfvok"/><path class="eul4pkbhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:group-duotone-sharp" {...props}></Icon>
<style>
:global(.ei2ayfvok) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 17v-5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1");
}

:global(.eul4pkbhp) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7h7v5H7zm3 5h7v5h-7zM3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
