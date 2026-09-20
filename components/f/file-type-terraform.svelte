<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wfzq7r5zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-terraform" {...props}></Icon>
<style>
:global(.wfzq7r5zj) {
  fill: var(--svg-color--813cf3, #813cf3);
  d: path("m12.042 6.858l8.029 4.59v9.014l-8.029-4.594zM20.5 20.415l7.959-4.575V6.887L20.5 11.429zM3.541 11.01l8.03 4.589V6.59L3.541 2zm8.501 14.4L20.071 30v-9.043l-8.029-4.589z");
}

</style>
