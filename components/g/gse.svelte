<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa2bnwedb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:gse" {...props}></Icon>
<style>
:global(.qa2bnwedb) {
  fill: var(--svg-color--24abcd, #24abcd);
  d: path("M17.625 12a5.626 5.626 0 0 1-9.602 3.977A5.625 5.625 0 0 1 12 6.375V3a9 9 0 1 0 9 9zm0-3.938V12h-3.938V8.062zm0 0v-2.25h2.25v2.25z");
}

</style>
