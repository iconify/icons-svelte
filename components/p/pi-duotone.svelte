<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zzkrtobrt"/><path class="u0d0qdwvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:pi-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.u0d0qdwvo) {
  d: path("M232 172a36 36 0 0 1-72 0V72H96v128a8 8 0 0 1-16 0V72h-8a40 40 0 0 0-40 40a8 8 0 0 1-16 0a56.06 56.06 0 0 1 56-56h152a8 8 0 0 1 0 16h-48v100a20 20 0 0 0 40 0a8 8 0 0 1 16 0");
}

:global(.zzkrtobrt) {
  d: path("M196 200H88V64h80v108a28 28 0 0 0 28 28");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
