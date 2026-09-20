<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qmotbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:present-to-all-sharp" {...props}></Icon>
<style>
:global(.c4qmotbik) {
  fill: currentColor;
  d: path("M11.5 15.308h1v-4.689l2.1 2.095l.713-.714L12 8.692L8.692 12l.714.708l2.094-2.094zM3 19V5h18v14z");
}

</style>
