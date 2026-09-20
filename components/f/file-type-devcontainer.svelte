<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="djoj4qpvd"/><path class="cpzplvrrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-devcontainer" {...props}></Icon>
<style>
:global(.cpzplvrrm) {
  fill: var(--svg-color--add1ea, #add1ea);
  d: path("m10.777 22.742l-1.434-1.394l3.386-3.483l-3.383-3.448l1.428-1.4l4.751 4.842zm10.643-3.641l1.434-1.395l-3.386-3.482l3.383-3.448l-1.428-1.4l-4.751 4.842z");
}

:global(.djoj4qpvd) {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--193e63, #193e63);
}

</style>
