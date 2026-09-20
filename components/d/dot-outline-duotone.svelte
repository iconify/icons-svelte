<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mmheh-5yj"/><path class="bb7jpy3uj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dot-outline-duotone" {...props}></Icon>
<style>
:global(.bb7jpy3uj) {
  d: path("M128 96a32 32 0 1 0 32 32a32 32 0 0 0-32-32m0 48a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mmheh-5yj) {
  d: path("M152 128a24 24 0 1 1-24-24a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
