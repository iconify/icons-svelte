<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":373};
const content = `<path class="ikl1hfb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:bulma" {...props}></Icon>
<style>
:global(.ikl1hfb8q) {
  fill: var(--svg-color--00d1b2, #00d1b2);
  d: path("M0 256L23.273 93.091L116.364 0l116.363 116.364l-69.818 69.818L256 279.273l-139.636 93.091z");
}

</style>
