<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mc0m_1psp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-u-left-down-thin" {...props}></Icon>
<style>
:global(.mc0m_1psp) {
  fill: currentColor;
  d: path("M204 88v88a4 4 0 0 1-8 0V88a52 52 0 0 0-104 0v126.34l41.17-41.17a4 4 0 0 1 5.66 5.66l-48 48a4 4 0 0 1-5.66 0l-48-48a4 4 0 0 1 5.66-5.66L84 214.34V88a60 60 0 0 1 120 0");
}

</style>
