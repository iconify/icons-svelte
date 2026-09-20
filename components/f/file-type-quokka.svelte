<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rkgiwqbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-quokka" {...props}></Icon>
<style>
:global(.rkgiwqbgu) {
  fill: var(--svg-color--fc6515, #fc6515);
  d: path("M2 16h14V2h14v28H2z");
}

</style>
