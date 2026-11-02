<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hdn2tovqs"/><path class="l-bd8kbsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:crown-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hdn2tovqs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.832 3.445l3.395 5.093l4.148-3.319a1.002 1.002 0 0 1 1.609.96l-2 11A1 1 0 0 1 19 18H5c-.483 0-.897-.346-.984-.821l-2-11a1.001 1.001 0 0 1 1.609-.96l4.148 3.319l3.395-5.093a1 1 0 0 1 1.664 0");
}

:global(.l-bd8kbsd) {
  d: path("M5 20h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
