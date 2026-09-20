<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<circle class="f0r-2x1bp"/><path class="m7mjk89gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:esbuild" {...props}></Icon>
<style>
:global(.f0r-2x1bp) {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--ffcf00, #ffcf00);
}

:global(.m7mjk89gp) {
  fill: var(--svg-color--191919, #191919);
  d: path("M69.285 58.715L138.571 128l-69.286 69.285l-16.97-16.97L104.629 128L52.315 75.685zm76.8 0L215.371 128l-69.286 69.285l-16.97-16.97L181.429 128l-52.314-52.315z");
}

</style>
