<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8zrwwqiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-bulk" {...props}></Icon>
<style>
:global(.d8zrwwqiw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.543 3.428l10 6a2.998 2.998 0 0 1 0 5.144l-10 6A2.998 2.998 0 0 1 5 18V6a3 3 0 0 1 4.543-2.572");
}

</style>
