<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bs48w7boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:list-dashes-bold" {...props}></Icon>
<style>
:global(.bs48w7boo) {
  fill: currentColor;
  d: path("M84 64a12 12 0 0 1 12-12h120a12 12 0 0 1 0 24H96a12 12 0 0 1-12-12m132 52H96a12 12 0 0 0 0 24h120a12 12 0 0 0 0-24m0 64H96a12 12 0 0 0 0 24h120a12 12 0 0 0 0-24M56 52H40a12 12 0 0 0 0 24h16a12 12 0 0 0 0-24m0 64H40a12 12 0 0 0 0 24h16a12 12 0 0 0 0-24m0 64H40a12 12 0 0 0 0 24h16a12 12 0 0 0 0-24");
}

</style>
