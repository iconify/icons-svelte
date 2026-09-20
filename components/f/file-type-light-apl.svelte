<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d9qthdb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-apl" {...props}></Icon>
<style>
:global(.d9qthdb2h) {
  d: path("M30 28.275L16 2L2 28.275h12.162V30h3.676v-1.725Zm-12.162-3.449V13.161l6.215 11.665Zm-9.891 0l6.215-11.665v11.665Z");
}

</style>
