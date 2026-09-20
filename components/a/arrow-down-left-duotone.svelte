<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sbh7v-m9n"/><path class="hf26w-b6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-down-left-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hf26w-b6t) {
  d: path("M197.66 58.34a8 8 0 0 0-11.32 0L116 128.69L69.66 82.34A8 8 0 0 0 56 88v104a8 8 0 0 0 8 8h104a8 8 0 0 0 5.66-13.66L127.31 140l70.35-70.34a8 8 0 0 0 0-11.32M72 184v-76.69l38.34 38.34L148.69 184Z");
}

:global(.sbh7v-m9n) {
  d: path("M168 192H64V88Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
