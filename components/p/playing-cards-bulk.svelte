<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ta8z1g-bc"/><path class="q_8k9vy7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:playing-cards-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.q_8k9vy7k) {
  d: path("M8 2h10a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H8a1 1 0 0 1 0-2m2.832 8.445l2 3a1 1 0 0 1 0 1.11l-2 3a1 1 0 0 1-1.664 0l-2-3a1 1 0 0 1 0-1.11l2-3a1 1 0 0 1 1.664 0M9.202 14L10 15.197L10.798 14L10 12.803Z");
}

:global(.ta8z1g-bc) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 9a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
