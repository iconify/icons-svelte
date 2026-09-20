<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="z9gni8buk"/><path class="szquu4vkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-teal" {...props}></Icon>
<style>
:global(.szquu4vkp) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.42 7.32h7v7h-7z");
}

:global(.z9gni8buk) {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--00aab4, #00aab4);
}

</style>
