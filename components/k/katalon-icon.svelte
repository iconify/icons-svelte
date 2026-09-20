<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":393};
const content = `<path class="qef7669wi"/><path class="kir1pdbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:katalon-icon" {...props}></Icon>
<style>
:global(.kir1pdbpt) {
  d: path("M128.001 0L0 130.725v130.726h128.001l127.958-130.726V0z");
}

:global(.qef7669wi) {
  fill: var(--svg-color--19d89f, #19d89f);
  d: path("M256 261.407H127.998v130.725H256z");
}

</style>
