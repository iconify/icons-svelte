<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xn7uhacnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-mondoo" {...props}></Icon>
<style>
:global(.xn7uhacnq) {
  fill: var(--svg-color--6e45e2, #6e45e2);
  d: path("M9.03 9.03A6.97 6.97 0 0 0 2.06 16a6.97 6.97 0 0 0 6.97 6.971zm0 6.97A6.97 6.97 0 0 0 16 22.971a6.97 6.97 0 0 0 6.971-6.97a6.97 6.97 0 0 0-6.97-6.972A6.97 6.97 0 0 0 9.028 16m13.942 0v6.97A6.97 6.97 0 0 0 29.94 16a6.97 6.97 0 0 0-6.968-6.97z");
}

</style>
