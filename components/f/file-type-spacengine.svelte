<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cqsms7hgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-spacengine" {...props}></Icon>
<style>
:global(.cqsms7hgb) {
  fill: var(--svg-color--4780f5, #4780f5);
  d: path("M24 5h2v22h-2zm-5 4.409L6 13.941v2.13l13 5v-2.142L8.906 15.046L19 11.527z");
}

</style>
