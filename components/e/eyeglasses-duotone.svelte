<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="bin13jbhb"/><path class="z1w0cebfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:eyeglasses-duotone" {...props}></Icon>
<style>
:global(.bin13jbhb) {
  d: path("M104 164a36 36 0 1 1-36-36a36 36 0 0 1 36 36m84-36a36 36 0 1 0 36 36a36 36 0 0 0-36-36");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.z1w0cebfw) {
  d: path("M200 40a8 8 0 0 0 0 16a16 16 0 0 1 16 16v58.08A44 44 0 0 0 145.68 152h-35.36A44 44 0 0 0 40 130.08V72a16 16 0 0 1 16-16a8 8 0 0 0 0-16a32 32 0 0 0-32 32v92a44 44 0 0 0 87.81 4h32.38a44 44 0 0 0 87.81-4V72a32 32 0 0 0-32-32M68 192a28 28 0 1 1 28-28a28 28 0 0 1-28 28m120 0a28 28 0 1 1 28-28a28 28 0 0 1-28 28");
}

</style>
