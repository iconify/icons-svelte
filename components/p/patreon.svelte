<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":247};
const content = `<path class="gu0kgm4to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:patreon" {...props}></Icon>
<style>
:global(.gu0kgm4to) {
  fill: var(--svg-color--ff424d, #ff424d);
  d: path("M45.136 0v246.35H0V0zm118.521 0C214.657 0 256 41.343 256 92.343s-41.343 92.343-92.343 92.343s-92.343-41.344-92.343-92.343S112.658 0 163.657 0");
}

</style>
