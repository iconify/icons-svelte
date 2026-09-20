<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="cislsvbjx"/><path class="y5hdhcc5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-esbuild" {...props}></Icon>
<style>
:global(.cislsvbjx) {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--ffcf00, #ffcf00);
}

:global(.y5hdhcc5z) {
  fill: var(--svg-color--191919, #191919);
  d: path("m18.2 23.8l-2.4-2.4l5.5-5.5l-5.5-5.5L18.2 8l7.8 7.8zm-8.4 0l-2.4-2.4l5.5-5.5l-5.5-5.5L9.8 8l7.8 7.8z");
}

</style>
